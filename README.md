# Task-4-_Telco-Customer-Churn-Prediction-Machine-Learning-Project
This project analyzes the Telco Customer Churn dataset and builds a machine learning model to predict whether a customer will churn. The work includes data cleaning, exploratory analysis, feature engineering, model training, and performance evaluation.

 Steps Performed:-

-Cleaned TotalCharges column and handled missing values

-Converted all columns to lowercase

-Dropped customerid (not useful for prediction)

-Performed EDA on churn, tenure, charges, contract, and internet service

-Applied LabelEncoder and One-Hot Encoding for categorical data

-Split dataset into training and testing sets

-Trained Random Forest Classifier

-Evaluated model using accuracy score

-Analyzed feature importance to understand churn drivers
 
 Key Insights:-

-Customers with low tenure churn more frequently

-Month-to-month contract users have the highest churn

-Higher monthly charges lead to higher churn

-Fiber optic users churn more than DSL users

-Lack of OnlineSecurity or TechSupport increases churn

Senior citizens show a higher churn rate

Random Forest performed better than Logistic Regression
