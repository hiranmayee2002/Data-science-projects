#Objective
The goal of this project is to predict whether a company is at risk of bankruptcy or not, based on its financial indicators. This helps investors, banks, and businesses take preventive action early.
🔹 Dataset
The dataset usually contains financial ratios and risk indicators of companies, such as:
1)Industrial risk
2)Management risk
3)Financial flexibility
4)redibility
5)Competitiveness
6)Operating risk

Class (Target → Bankruptcy or Non-bankruptcy)

🔹 Approach

1)Data Loading & Cleaning
Load CSV file (bankruptcy prevention.csv).
Handle missing values, check data types, and clean the dataset.

2)Exploratory Data Analysis (EDA)
Visualize class balance (how many bankrupt vs. non-bankrupt companies).
Check correlation between features and bankruptcy risk.

3)Feature Engineering
Encode categorical values (like bankruptcy → 1, non-bankruptcy → 0).
Normalize or scale features if needed.

4)Model Building
Train machine learning models like:
Logistic Regression
Decision Tree
Random Forest
XGBoost / Gradient Boosting
Compare accuracy, precision, recall, F1-score.

5)Model Evaluation
Use Confusion Matrix to check how well the model detects bankruptcy vs. non-bankruptcy.
Use ROC-AUC curve to measure performance.

6)Deployment (Optional)
Save the model (joblib or pickle).
Create a simple UI (Flask/Streamlit) where users can input company data and get predictions.

🔹 Outcome
A trained model that can predict bankruptcy risk with good accuracy.
Insights on which factors (e.g., management risk, operating risk) contribute most to bankruptcy.
A tool for financial institutions or businesses to prevent bankruptcy early.

⚡ Example use case:
A bank can use this model before giving a loan to check if a company is likely to repay or default.

A bank can use this model before giving a loan to check if a company is likely to repay or default.
