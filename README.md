# credit-risk-classification-Model

Predicts customer credit risk (Good vs. Bad) using demographic, account, and enquiry data from a MySQL database. Built with SQL, pandas, and XGBoost.

Result: Gini score of 38.75, beating the 37.9 benchmark.

## Approach
- Extracted & joined 3 MySQL tables (600K+ records)
- Cleaned data, engineered ~37 features (payment history, ratios, aggregations)
- Handled class imbalance (4.2% "Bad") with SMOTE
- Compared Logistic Regression, Random Forest, Gradient Boosting, XGBoost

## Tech Stack
Python (pandas, scikit-learn, XGBoost, imbalanced-learn), MySQL, SQLAlchemy


