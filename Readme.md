🏦 # Loan Approval Prediction using Logistic Regression

This project aims to predict whether a loan application will be approved based on applicant information, using logistic regression models for binary classification. Developed as part of a machine learning course project using the Loan Approval Classification dataset from Kaggle.

📌 ## Project Objectives
Predict loan approval (Loan_Status: Y/N → 1/0)

⚙️ ## Models Overview
Model 1 – Baseline Logistic Regression

Uses 1 single feature

Helps understand the predictive power of a single variable

Serves as the simplest benchmark

Model 2 – Logistic Regression with 3 Features

Uses 3 selected features (based on domain knowledge or correlation)

Provides a balance between simplicity and performance

Demonstrates how adding relevant features improves prediction

Model 3 – Logistic Regression with Multiple Features

Uses many or all relevant features

Includes both numerical and encoded categorical variables

Maximizes model complexity and predictive capability without tuning





























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
        name = Kalliopi Georgiou
        email = kalliopi.a.georgiou@gmail.com
        username = KalliopiGeorgiou
```
