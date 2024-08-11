# Housing-Price-Prediction
This project focuses on predicting house prices using various machine learning models. The dataset used is a CSV file containing data on various features of houses, such as TotalBsmtSF, SalePrice, and other relevant attributes. Below is a detailed description of the project:

Project Overview
The primary goal of this project is to predict the house prices using a dataset that includes various features related to the properties. The project involves several steps, including data cleaning, exploratory data analysis, feature encoding, and model training using different regression techniques.

Dataset Details
The dataset contains the following columns:

SalePrice: The target variable, representing the price at which the house was sold.
TotalBsmtSF: The total square footage of the basement area.
Other features: Various other features related to the properties, including categorical and numerical data.
Steps Involved
Data Loading and Initial Exploration
The dataset is loaded using pandas, and the first few rows, along with the shape and information of the dataset, are printed.
Missing values are visualized using a bar plot.
Data Cleaning
Categorical columns are filled with the mode (most frequent value), and numerical columns are filled with the mean.
After filling missing values, the number of null values is checked again.
Data Analysis
The columns are categorized into integer, float, and object types.
Unique values in categorical columns are printed and visualized using count plots.
Outliers in the TotalBsmtSF column are detected and removed using a box plot and filtering.
Correlation between features is visualized using a heatmap after encoding categorical variables.
Feature Encoding and Normalization
Categorical features are encoded using LabelEncoder.
The features are then split into training and validation sets.
The data is normalized using StandardScaler.
Model Training
Several regression models are trained, including LinearRegression, XGBRegressor, Lasso, RandomForestRegressor, and Ridge.
The mean absolute error (MAE) is calculated for both training and validation sets.
Model Comparison
A scatter plot is created to compare the predicted values with the actual values for the different models.
Conclusion
The project provides a comprehensive approach to predicting house prices using multiple regression models. By analyzing the dataset, cleaning the data, and applying various machine learning techniques, the project demonstrates how different models perform in predicting the target variable, SalePrice. The visualizations and error metrics help in understanding the model performance and choosing the best model for the prediction task.
