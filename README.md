# Customer Churn Prediction

## Project Overview

This project uses Machine Learning to predict whether a customer is likely to churn.
The goal is to identify customers who are at higher risk of leaving so that businesses can take retention actions.

## Objectives

- Analyze customer churn patterns
- Identify important factors affecting churn
- Build Machine Learning models to predict churn
- Categorize customers based on churn risk
- Compare different ML models
- Build a customer retention dashboard using Streamlit

## Dataset

The project uses a customer churn dataset containing information about:

- Customer demographics
- Tenure
- Contract type
- Payment method
- Monthly charges
- Total charges
- Internet and phone services

## Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate customers
- Removed unnecessary columns
- Removed potential data leakage such as churn reason
- Converted Total Charges into numeric format
- Handled missing values
- Created Risk Category
- Encoded categorical variables using One-Hot Encoding
- Scaled numerical features
- Split data into training and testing sets

## Machine Learning Models

The project will compare multiple classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Evaluation Metrics

Models will be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Business Impact

The model can help businesses identify customers who are more likely to churn and support targeted retention strategies such as:

- Special offers for high-risk customers
- Encouraging long-term contracts
- Promoting automatic payment methods
- Customer-specific retention campaigns

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Streamlit
