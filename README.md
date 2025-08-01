# 🏦 Loan Status Prediction using Logistic Regression
📘 Project Overview
LoanTap is an online platform delivering customized loan products to millennials. This case study focuses on building a credit underwriting model to predict whether a loan applicant is likely to repay the loan or not, using logistic regression.

✅ Objective: Predict the loan status (approved or rejected) based on applicant information, and provide recommendations based on prediction outcomes.

📂 Dataset Information
File Used: LoanTapData.csv

Each row represents a loan application with multiple attributes. The target variable is loan_status.

🔑 Features Used
Feature	Description
loan_amnt	Applied loan amount
term	Number of loan payments (in months)
int_rate	Interest rate on the loan
installment	Monthly payment if loan originates
grade / sub_grade	LoanTap assigned loan grade/subgrade
emp_title / emp_length	Employment title & length (in years)
home_ownership	Ownership status of home
annual_inc	Annual income of applicant
verification_status	Whether income was verified
loan_status	✅ Target variable (Loan approved/rejected)
purpose / title	Purpose and title of the loan
dti	Debt-to-Income ratio
revol_util	Credit utilization ratio
total_acc / open_acc	Total & open credit lines
mort_acc	Number of mortgage accounts
pub_rec / pub_rec_bankruptcies	Public records & bankruptcies
address	Applicant address

🧠 Concepts & Techniques Applied
📊 Exploratory Data Analysis (EDA)

🔧 Feature Engineering

⚖️ Handling Class Imbalance (SMOTE)

🔍 Logistic Regression (Baseline & Tuned Models)

📈 Model Evaluation: Accuracy, Precision, Recall, F1-Score, ROC-AUC

✅ Precision vs Recall Trade-off

🧪 Hyperparameter Tuning using GridSearchCV

🧪 Model Building
The main model used: Logistic Regression

Steps followed:

Data Cleaning & Preprocessing: Handling null values, encoding, and transformations

Exploratory Data Analysis: Identifying trends, correlations, and class imbalance

Feature Engineering: Creating and selecting the most important predictors

Model Training: Logistic regression using sklearn

Evaluation Metrics:

Confusion Matrix

Classification Report

ROC-AUC Curve

Hyperparameter Tuning: Using GridSearchCV to optimize C and penalty

📊 Results & Insights
Achieved balanced precision and recall through tuning

Addressed class imbalance using SMOTE

Important factors influencing loan approval included: annual_inc, dti, emp_length, and home_ownership

🛠️ Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (Logistic Regression, GridSearchCV, SMOTE)

Jupyter Notebook

📌 Future Enhancements
Deploy the model via Streamlit

Explore other classifiers like Random Forest, XGBoost

Integrate explainability tools like SHAP or LIME

Build a frontend for user interaction

🔗 Connect with Me
Pulkit Kapoor
📧 kapoor.pulkit660@gmail.com
📘 LinkedIn -https://www.linkedin.com/in/pulkit-kapoor-39b26452/
🐙 GitHub

