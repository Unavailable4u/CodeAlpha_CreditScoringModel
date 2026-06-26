# Credit Scoring Model — CodeAlpha ML Internship

## Project Overview
Binary classification model to predict loan default using historical financial data.

## Dataset
Give Me Some Credit — Kaggle (150,000 records, 10 features)  
Download from: https://www.kaggle.com/c/GiveMeSomeCredit

## Results
| Model | ROC-AUC | F1 (Default) |
|---|---|---|
| Logistic Regression | 0.773 | 0.28 |
| Decision Tree | 0.844 | 0.32 |
| Random Forest | 0.854 | 0.32 |

## Key Steps
- EDA & visualizations
- Missing value imputation & outlier removal
- Feature engineering (TotalLatePayments, IncomePerDependent, AgeGroup)
- SMOTE to handle 6.68% class imbalance
- Trained 3 models and compared with ROC-AUC

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/credit_scoring.ipynb