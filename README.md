## Case Study 2: Credit Card Fraud Detection

The objective is to detect fraudulent credit card transactions using
XGBoost. Since fraud transactions are highly imbalanced compared to genuine
transactions, SMOTE is applied to the training data.

The model is evaluated using ROC-AUC, different decision thresholds are
tested to improve fraud detection, and feature importance scores are used
to identify the most influential transaction features.
