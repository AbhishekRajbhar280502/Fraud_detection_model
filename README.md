# Fraud_detection_model
# 🛡️ Fraud Detection in Financial Transactions
This project aims to build a machine learning model to detect fraudulent financial transactions using a real-world dataset with over 6 million records.
 #🔍 Problem Statement
Identify whether a transaction is fraudulent (isFraud = 1) or not (isFraud = 0) using various features like transaction type, amount, account balances, and system flags.

 #Dataset
Contains 10 columns and ~6.3 million rows.

Key features: type, amount, oldbalanceOrg, newbalanceOrg, newbalanceDest, isFlaggedFraud

Target variable: isFraud

# Workflow
Data cleaning (outliers, missing values, multicollinearity)

Feature encoding and selection

Train-test split with stratification

Model training using Random Forest Classifier

Performance evaluation using Precision, Recall, F1-Score, ROC-AUC

Feature importance analysis

📈 Results
Accuracy: 99.96%

ROC-AUC: 0.90

Precision (Fraud): 72%

Recall (Fraud): 27%
