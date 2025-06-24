Black Friday Sales Prediction
This project aims to build a machine learning model to predict the purchase amount of customers during Black Friday sales based on their demographic and transaction details. The dataset contains over 500,000 records and includes features such as age, gender, city category, years spent in the current city, occupation, and product categories. The ultimate goal is to help a retail company estimate sales and optimize pricing or marketing strategies.

The data used in this project was obtained from a publicly available dataset. After loading the data, initial exploration and analysis were performed to understand the distribution of purchases across different categories such as gender, age groups, city types, and marital status. Several visualizations were created to capture these insights.

Missing values in the dataset were handled by filling them with zero, assuming no purchase in those categories. Categorical variables such as Gender, Age, and City_Category were encoded using label encoding, and dummy variables were created for the 'Stay_In_Current_City_Years' feature. The dataset was then split into training and testing sets to evaluate model performance on unseen data.

Multiple regression algorithms were applied to model the purchase predictions. These include Linear Regression, Ridge and Lasso Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor. All models were evaluated using the Root Mean Squared Error (RMSE) metric to assess prediction accuracy. Among all, the XGBoost model performed the best with the lowest RMSE of approximately 2879.

Additional steps included scaling the features for linear models, plotting feature importances using XGBoost, and comparing all model performances using a bar chart. The project demonstrates the end-to-end pipeline of data cleaning, exploratory data analysis, feature engineering, model training, evaluation, and comparison in a supervised regression task.

This repository contains the complete Python code for the project along with visualizations and model evaluations. It is suitable for showcasing to employers, submitting as an internship project, or using as a reference for similar machine learning tasks.

