# CodeAlpha Credit Scoring Model
## Overview
Predicts creditworthiness using an XGBoost model on financial data.
## Dataset
- Features: person_age, person_income, person_home_ownership, person_emp_length, loan_intent, loan_grade, loan_amnt, loan_int_rate, loan_percent_income, cb_person_default_on_file, cb_person_cred_hist_length, debt_to_income
- Target: loan_status (0 or 1)
- Missing Values: Handled 895 in person_emp_length, 3116 in loan_int_rate with median imputation
## Setup
- Run in Google Colab
- Install: `pip install pandas sklearn seaborn xgboost`
## Results
- Precision: 0.818
- Recall: 0.809
- F1-Score: 0.814
- ROC-AUC: 0.950
## Files
- CodeAlpha_Credit_Scoring_Final.ipynb: Main code
- roc_curve_xgb.png: ROC curve
- confusion_matrix_xgb.png: Confusion matrix
- feature_importance_xgb.png: Feature importance
