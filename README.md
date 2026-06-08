# home-credit-default-risk
Credit Default Risk Prediction using Machine Learning (Rakamin x Home Credit Project)
# Home Credit Default Risk Prediction

## Project Overview

This project aims to predict customer loan default risk using machine learning techniques. The analysis was conducted on the Home Credit Default Risk dataset to identify key risk factors and support better credit decision-making.

## Business Problem

Loan defaults can lead to significant financial losses for lending institutions. Therefore, identifying high-risk applicants before loan approval is crucial for effective credit risk management.

## Objectives

- Identify factors associated with loan default risk.
- Build a predictive model for default classification.
- Generate actionable business insights to support credit decisions.

## Dataset

Home Credit Default Risk Dataset

- 307,511 records
- 122 original features
- Binary target:
  - 0 = Non-default
  - 1 = Default

## Data Preprocessing

- Removed features with more than 60% missing values.
- Imputed missing values.
- Applied One-Hot Encoding.
- Prepared data for machine learning modeling.

## Machine Learning Models

- Logistic Regression
- Random Forest

## Model Performance

| Model | ROC-AUC |
|---------|---------|
| Logistic Regression | 0.748 |
| Random Forest | 0.711 |

The Logistic Regression model achieved the best performance and was selected as the final model.

## Key Business Insights

### Insight 1
Only 8.07% of customers are default customers, indicating a highly imbalanced dataset.

### Insight 2
External credit scores (EXT_SOURCE_2 and EXT_SOURCE_3) are the strongest predictors of default risk.

## Business Recommendations

- Implement a credit scoring system for early risk detection.
- Apply additional verification for high-risk applicants.
- Prioritize external credit scores during credit assessment.
- Improve future model performance using SMOTE, XGBoost, or LightGBM.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Author

Atiqoh Fauzi
