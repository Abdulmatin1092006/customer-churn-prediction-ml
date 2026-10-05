# Customer Churn Prediction Using Machine Learning

A machine learning project that predicts whether a telecom customer is likely to churn using supervised classification algorithms.

## 📌 Project Overview

Customer churn refers to a customer discontinuing a service. Predicting churn can help companies identify customers who may be at risk of leaving and take appropriate retention measures.

In this project, different machine learning classification algorithms are trained and evaluated on a telecom customer dataset.

## 🎯 Objectives

- Analyze customer information and identify patterns related to churn.
- Perform basic exploratory data analysis (EDA).
- Preprocess numerical and categorical features.
- Train multiple classification models.
- Compare model performance using evaluation metrics.
- Select the model with the best F1-score.
- Make a sample customer churn prediction.

## 📊 Dataset

The project uses the IBM Telco Customer Churn dataset.

The dataset contains customer demographic information, service details, account information, and the target variable `Churn`.

Dataset source:

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🔍 Project Workflow

1. Load the dataset
2. Clean and preprocess the data
3. Perform exploratory data analysis
4. Split data into training and testing sets
5. Apply preprocessing to numerical and categorical features
6. Train classification models
7. Compare model performance
8. Evaluate the selected model
9. Analyze important features
10. Generate a sample prediction

## 🤖 Machine Learning Models

The following classification algorithms were compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

## 📈 Model Selection

Logistic Regression achieved the highest F1-score among the models tested in this project and was selected as the final model.

Although Gradient Boosting achieved slightly higher accuracy, Logistic Regression provided the best F1-score, making it the selected model for this project.

## 🔎 Key Findings

- Customers with month-to-month contracts showed a higher churn rate compared with customers having longer-term contracts.
- Customers with longer tenure generally showed lower churn.
- Monthly charges were generally higher among customers who churned.
- Customer and service-related features can provide useful information for predicting churn.

## 📁 Repository Structure

```text
customer-churn-prediction-ml/
│
├── customer_churn_prediction_ml.ipynb
├── README.md
└── requirements.txt
