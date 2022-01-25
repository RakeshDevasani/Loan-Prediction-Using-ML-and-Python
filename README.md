# Loan-Prediction-Using-ML-and-Python
Building a model which can predict whether an applicant's loan will be approved or not
# Overview
1. Problem Statement
2. Imorting the Libraries and datasets
3. Exploratory Data Analysis (EDA)
   * Univariate Analysis
   * Bivariate Analysis
4. Feature Engineering
5. Feature Selection
6. Model Building
   * Random Forest
   * XGBoost
   * Support Vector Machine
   * Decision Tree
   * Logistic Regression
   * K Nearest Neighbors(KNN)
7. Model Selection
8. Hyperparameter Tuning
9. Predicting the sales for test dataset
# Insights
1. 80% of applicants in the dataset are male.
2. Around 65% of the applicants in the dataset are married.
3. Around 80% of the applicants are Graduate.
4. Around 15% of applicants in the dataset are self-employed.
5. More than 80% of applicants have good credit_History(repaid their debts)
6. Around 70% of applicants loans are approved.
7. Most of the applicants don't have any dependents.
8. Most of the applicants are from the Semiurban area and urban area.
9. Average CoapplicantIncome for getting a loan is 1500.
10. Less loan amount have little high chance of approvals.
11. Married applicants have 8% higher chance of loan approval than Unmarried.
12. Graduates have 10% higher chance loan approval than Non Graduates.
13. loan approvals is not depending on self employed.
14. Good Credit History applicants has very high(80%) chance of loan approval.
15. Applicants having 2 Dependents have highest(75%) chance of loan approvals.
16. Semiurban Applicants 10% higher chance of loan approval than urban and rural.
# Results
Random Forest Accuracy Score = 0.772358

After Hyperparameter Tuning = 0.7886178861788617

In Confusion Matrix FP=25 i.e., model predicted positive but it is false

Precision of model for Non Approval is 0.947368 (its good as company don't want to approve loans to those can't payback).
