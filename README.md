# House-price-prediction

Property Price Prediction
This repository contains a project focused on predicting property prices using machine learning techniques. The project involves preprocessing property data and applying linear regression to predict prices based on various features.

Data
The dataset includes the following features:

Bathrooms: Number of bathrooms in the property.
Furnishing: Furnishing status of the property (e.g., Furnished, Semi-Furnished).
Area: Size of the property in square feet.
Price: Price of the property (target variable).
bhk: Number of bedrooms in the property.
Locality: Location of the property.
Data Preprocessing
Dropped Unnecessary Columns: Columns like Bedrooms and Price_per_sqft were removed as they were not used for the prediction.
Encoded Categorical Variables: Furnishing and Locality were encoded using dummy variables.
Furnishing: Converted into dummy variables (Furnishing_Furnished, Furnishing_Semi-Furnished).
Locality: Converted into dummy variables for each locality.
Feature Selection: The final features used for prediction include Bathrooms, Area, bhk, and encoded locality features.
Model Implementation
Algorithm: Linear Regression
Model Parameters: fit_intercept=False
Evaluation: The model is evaluated using Mean Squared Error (MSE).
