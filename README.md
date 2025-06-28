## 🏦 Loan Approval Prediction using Logistic Regression

This project aims to predict whether a loan application will be approved based on applicant information, using logistic regression models for binary classification.

Developed as part of a machine learning course project using the Loan Approval Classification dataset from Kaggle.

## 📌 Project Objectives

Predict loan approval (Loan_Status: Y/N → 1/0)

Compare performance across 3 logistic regression variations:
1) Model 1 - Baseline model: A simple logistic regression using only 1 predictor feature to estimate loan approval. This acts as the baseline model.
2) Model 2 – Logistic Regression with 3 Key Features: A logistic regression model using 3 important features. This is a step toward better performance with low complexity.
3) Model 3 – Logistic Regression with many numerical features: A full-featured logistic regression using many scaled numerical features.

## 📁 Project Structure

├── Dataset for Final Project/
│   └── Loan_Approval.csv      # Input Dataset
├── notebooks/
│   ├── LoanApprovalFinalProject.ipynb     
├── requirements.txt
├── README.md
└── .gitignore

## 📊 Dataset Overview
Source: Kaggle – Loan Approval Classification

Records: 45000 applications and 14 variables

Target variable: Loan_Status (Y → 1, N → 0)

Features:

Categorical: person_gender, person_education, person_home_ownership, loan_intent, previous_loan_defaults_on_file

Numerical: person_income, person_emp_exp, loan_amnt, loan_int_rate, loan_percent_income, cb_person_cred_hist_length, credit_score

🎯 Target Variable: Loan Status


## ⚙️ Models and Techniques Used

Logistic Regression 
Preprocessing:
Handling missing values
Encoding categorical variables
Feature scaling

## Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

## How to run
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
pip install -r requirements.txt --no-deps
```

```
jupyter notebook \
    --notebook-dir="." \
    --ip=0.0.0.0 --port=3225
```
```
python -m debugpy --listen 4444 test.py
```

```
fastapi dev main.py
```


## Enable push to git
```
nano ~/.gitconfig
```
```
code ~/.gitconfig
```


```
[user]
# Please adapt and uncomment the following lines:
        name = <Name>
        email = <github email>
        username = <github username>
```