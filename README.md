# customer-churn-prediction
# Customer Churn Prediction

Predicts telecom customer churn using Logistic Regression and Random Forest.

## Dataset
Telco Customer Churn dataset (Kaggle, ~7,000 customers)

## Models & Results
| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Logistic Regression | 0.803 | 0.652 | 0.556 | 0.600 |
| Random Forest | 0.790 | 0.634 | 0.495 | 0.556 |

**Logistic Regression performed best**, especially on recall — important since
catching customers likely to churn matters more than avoiding false alarms.

## Key Churn Drivers
- TotalCharges
- tenure
- MonthlyCharges

## Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn
