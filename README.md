# Loan Approval

![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-brightgreen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Overview
Predicting loan approval status using machine learning. This project analyzes historical loan application data to identify key factors influencing approval decisions.

## Dataset Description
The dataset contains 13 features with 614 entries:
- **Loan_ID**: Unique loan ID
- **Gender**: Applicant gender (Male/Female)
- **Married**: Marital status
- **Dependents**: Number of dependents
- **Education**: Education level
- **Self_Employed**: Self-employment status
- **ApplicantIncome**: Income amount
- **CoapplicantIncome**: Co-applicant income
- **LoanAmount**: Loan amount (thousands)
- **Loan_Amount_Term**: Repayment period (months)
- **Credit_History**: Credit history meets guidelines
- **Property_Area**: Property location
- **Loan_Status**: Approval status (Target)

## Methodology
1. **Data Preprocessing**:
   - Handling missing values
   - Feature engineering (Total Income, EMI)
   - Label encoding categorical features

2. **Exploratory Analysis**:
   - Univariate and bivariate analysis
   - Correlation analysis
   - Class distribution examination

3. **Modeling**:
   - Gradient Boosting classifier
   - Train-test split (80-20)
   - Performance metrics: Accuracy, Precision, Recall, F1, ROC-AUC

## Key Findings:
   - There is a correlation between applicant income and loan amount
   - Credit history has a very significant and direct impact on loan status
## Technologies Used
- Python 3.10
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
```bash
git clone https://github.com/realyashagarwal/loan-approval.git
cd loan-approval-prediction
pip install -r requirements.txt
