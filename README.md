What it Does(Description):-
This project predicts whether a loan application will be approved or rejected based on applicant details such as income, education, credit history, dependents, and property type. It is a classification problem where the target variable is Loan_Status (Yes/No).

How it Works:-
Data Loading
Reads the loan dataset (train.csv) containing applicant information.
Data Preprocessing
Drops irrelevant columns (Loan_ID).
Separates features (X) and target (y).
Handles missing values (fills Gender, Married, Credit_History, etc.).
Encodes categorical variables into numeric form for modeling.
Model Training
Builds machine learning classification models such as Logistic Regression, Decision Tree, Random Forest, or similar (common for loan prediction).
Trains them on applicant features to predict loan approval.
Evaluation
Compares models using accuracy (and possibly confusion matrix, precision, recall, F1-score).
Finds the best model for loan approval prediction.
Prediction
The trained model can take new applicant data and output whether the loan is likely to be approved.

Why it’s Useful

Automates the loan approval decision-making process.
Reduces manual effort and bias in financial institutions.
Highlights which applicant features (like income, credit history, education) influence approvals most.



