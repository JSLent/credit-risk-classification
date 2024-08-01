# Module 12 Report Template
## Overview of the Analysis
In this analysis, we were asked to build a machine learning model to predict the credit risk of loans. The aim of this analysis is to determine whether a loan is healthy `0` (low risk) or high risk `1` of defaulting. The dataset used for this analysis consisted of financial information about loans, including various features such as loan amount, interest rate, and borrower information.

The target variable, 'loan_status', had two possible values:

0: Healthy loan
1: High-risk loan

The stages of the machine learning process included:

### Data Preparation: 
Loading the dataset, separating the features and labels, and splitting the data into training and testing sets.
### Model Building: 
Using logistic regression to build a predictive model.
### Model Evaluation: 
Evaluating the model’s performance using metrics such as accuracy, precision, recall, and F1-score.

The logistic regression algorithm was chosen for its simplicity and effectiveness in binary classification problems.

## Results
Logistic Regression Model:
### Accuracy: 
99%
### Precision:
For label 0 (healthy loan): 1.00
For label 1 (high-risk loan): 0.85

### Recall:
For label 0 (healthy loan): 0.99
For label 1 (high-risk loan): 0.91

### F1-Score:
For label 0 (healthy loan): 1.00
For label 1 (high-risk loan): 0.88

## Summary
This logistic regression model demonstrates outstanding performance in predicting `0` or healthy loans, with very high precision, recall and F-1 score.  Although it has slightly lower precision and F-1 score, it also performs well predicting `1` high-risk loans. The model achieved an accuracy of 99%, indicating that it correctly predicts the loan status for 99% of the instances.  As a whole, this is a highly accurate and effective model in its ability to distinguish between healthy and high-risk loans.

## Recommendation
Based on the evaluation metrics, I recommend using the logistic regression model for predicting credit risk. The model’s high accuracy and strong performance in predicting both healthy and high-risk loans make it a reliable tool for credit risk assessment. The slightly lower precision for high-risk loans is acceptable given the overall high performance of the model.
