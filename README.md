# loan-approval-prediction
Loan approval prediction using Logistic Regression and machine learning.
## 📌 Project Overview

This project uses Machine Learning to predict whether a loan application will be **approved or rejected** based on applicant information.

The project uses **Logistic Regression**, a supervised machine learning algorithm commonly used for binary classification problems.

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict loan approval based on different applicant features such as:

- Gender
- Marital Status
- Number of Dependents
- Education
- Self Employment
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

The target variable is:

- `1` → Loan Approved
- `0` → Loan Rejected

---

## 📊 Dataset

The project uses the **Loan Prediction Dataset**.

The dataset contains information about loan applicants and their loan approval status.

### Target Variable

`Loan_Status`

- `Y` → Approved
- `N` → Rejected

The target variable was converted into numerical values:

- `Y` → `1`
- `N` → `0`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab 

---

## 🤖 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used mainly for classification problems.

In this project, Logistic Regression is used to classify loan applications into two classes:

```text
Approved
   or
Rejected
