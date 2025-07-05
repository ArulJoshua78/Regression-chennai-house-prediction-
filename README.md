Chennai House Price Prediction (Regression) - Machine Learning Project
This project applies supervised machine learning regression techniques to predict house prices in Chennai based on a variety of property and environmental features. It demonstrates my ability to handle real-world data, build and evaluate multiple regression models, and interpret model performance to make informed decisions.

Objective:
The primary goal of this project is to build an accurate regression model that can predict the market price of houses in Chennai using historical housing data. By experimenting with various algorithms and performance metrics, the project aims to determine the best-performing model for reliable price forecasting.

Dataset Features:
The dataset includes essential features that influence housing prices, such as:

Feature	Description
Area (sq.ft)	Total built-up area of the house
No. of Bedrooms	Number of bedrooms
Location	Locality within Chennai
Furnishing Status	Whether the house is furnished or not
Parking, Lift, Balcony	Additional amenities
Facing Direction	Orientation of the house
Target Variable	House Price (in INR)

Note: Actual features may vary depending on your data preprocessing and selection.

Tools & Technologies:
Python
Jupyter Notebook
Scikit-learn – Model development & evaluation
Pandas, NumPy – Data analysis
Matplotlib, Seaborn – Data visualization
StandardScaler – Feature scaling
R² Score – Performance metric

Workflow:
Data Preprocessing
Handled missing values
Encoded categorical variables (e.g., location, furnishing)
Scaled numeric features using StandardScaler
Model Building
Implemented and compared multiple regression models:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
K-Nearest Neighbors Regressor (KNN)
Model Evaluation
Used R² Score to evaluate model performance

Compared both training and testing scores to check for overfitting

✅ Results
Model	Training R²	Testing R²
Linear Regression	0.8114	0.8078
Decision Tree	1.0000	0.9565
SVR	-0.0207	-0.0142
KNN	0.9178	0.8631
Random Forest	0.9974	0.9813

🔹 Best Performing Model: RandomForestRegressor with 98.13% testing R² score, showing excellent generalization.
🔸 SVR was not suitable for this dataset due to poor performance.


 Skills Demonstrated
✅ Regression modeling and evaluation
✅ Data preprocessing and feature engineering
✅ Model selection and performance comparison
✅ Clean and reproducible ML code using Python
