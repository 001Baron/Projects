# Customer Churn Prediction

This project aims to predict customer churn using various machine learning models. The dataset includes customer demographics, account information, and services used.

## Table of Contents
- Introduction
- Dataset
- Data Preprocessing
- Modeling
- Results
- Conclusion
- Installation
- Usage
- Contributing
- License

## Introduction
Customer churn is when customers stop using a company's services. Predicting churn helps in retaining customers, which is crucial for businesses in competitive industries.

## Dataset
The dataset includes the following key columns:
- `gender`
- `tenure`
- `contract_type`
- `payment_method`
- `churn` (whether the customer churned)

## Data Preprocessing
Steps involved in data preprocessing:
1. Handling missing values
2. Converting data types
3. Scaling numerical features
4. Encoding categorical variables (label encoding and one-hot encoding)

## Modeling
The following machine learning models were used:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Logistic Regression

## Results
Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- Confusion Matrix

## Conclusion
The project demonstrates the effectiveness of different machine learning models in predicting customer churn. The results can help businesses take proactive measures to retain customers.

## Installation
To run this project, install the required packages using:
```bash
pip install -r requirements.txt
