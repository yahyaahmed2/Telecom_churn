# Telecom_churn
Machine learning application predicting customer churn in telecom company using logistic regression.


-I used logistic regression to either be 1 if customer will churn or 0 if no churn.

# Challenges faced and solution
**categorical values**: The data had a mix of numeric and categorical values so I had to use label encoding for binary values and one hot encoding for multi categorical values.

**One hot encoding generating false and true**: One hot encoding for some reason didn't generate numeric values by default and I had to define data type manually.

**Imbalanced dataset**:The churn was very imbalanced with No churn having much more values available than Churn so I used SMOTE(Synthetic minority Over-Sampling TEqnique) to balance the dataset.

# Technical Details
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **Algorithm**: Logistic Regression, SMOTE

# Dataset used
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
