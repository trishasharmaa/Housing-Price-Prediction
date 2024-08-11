# Housing-Price-Prediction
This project focuses on predicting house prices using various machine learning models. The dataset used is a CSV file containing data on various features of houses, such as TotalBsmtSF, SalePrice, and other relevant attributes. Below is a detailed description of the project:
# Project Overview
The primary goal of this project is to predict the house prices using a dataset that includes various features related to the properties. The project involves several steps, including data cleaning, exploratory data analysis, feature encoding, and model training using different regression techniques.


The project begins by loading the dataset and exploring its structure, including visualizing missing values. Data cleaning is performed by filling missing categorical values with the mode and numerical values with the mean. Outliers in the TotalBsmtSF column are detected and removed. The dataset is then analyzed, with categorical features being encoded using LabelEncoder, and the correlation between features is visualized using a heatmap. The data is split into training and validation sets, followed by normalization using StandardScaler. Various regression models, including LinearRegression, XGBRegressor, Lasso, RandomForestRegressor, and Ridge, are trained, and their performance is evaluated using mean absolute error (MAE). Finally, a scatter plot is created to compare the predicted values with the actual values across different models, allowing for a comparison of model performance.

# Conclusion
The project provides a comprehensive approach to predicting house prices using multiple regression models. By analyzing the dataset, cleaning the data, and applying various machine learning techniques, the project demonstrates how different models perform in predicting the target variable, SalePrice. The visualizations and error metrics help in understanding the model performance and choosing the best model for the prediction task.
