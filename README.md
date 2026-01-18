# Leading-Club-Loan-Data-Analysis-Project-
Analyzed historical Lending Club data to identify the key factors driving loan defaults. Built a classification model to predict borrower behavior, helping investors mitigate risk and optimize portfolio returns in a peer-to-peer lending environment.
The main goal is to identify patterns in borrower attributes that predict whether a loan will default (not fully paid), aiding lenders in risk assessment, loan approval decisions, and strategies like higher interest rates for risky applicants.

Key Dataset Features
Loan details: Amount, interest rate, grade, term (36/60 months).
Borrower info: FICO score, debt-to-income ratio (dti), employment length, home ownership.
Target: Binary 'not.fully.paid' (0: fully paid, 1: default).

Typical Analysis Steps
Data cleaning: Handle missing values, encode categoricals (e.g., LabelEncoder for grade), extract numerics from employment length.
EDA: Visualize defaults by grade, home ownership; check class imbalance (~80/20 fully paid vs. default).
Modeling: Neural networks (Keras/TensorFlow), SMOTE for balancing, metrics like AUC-ROC (0.75-0.85), confusion matrix.

Insights and Outcomes
Higher defaults correlate with lower loan grades, higher dti, shorter employment, and rentals/mortgages over ownership. Models help prioritize low-risk investments and improve collection strategies.
​
