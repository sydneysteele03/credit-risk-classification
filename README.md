# credit-risk-classification
Module 20 Challenge: Model Loan Risks

# Credit Risk Report 
The purpose of this report is to build a model that assesses the credibility and risk level of individuals applying for a loan. The model built is evaluated for its accuracy on predicting the risk and healthiness of credit loan borrowers. 

Description of Model 1 (Logistic Regression model with original data):
  * Accuracy of 99%, indicating this model fits the dataset very well and will predict loan risk well. 
  * Precision of 92%, meaning 92% of the predicted healthy or low risk borrowers were predicted correctly. 
  * Recall of 95%, meaning my model was 95% precise in predicting true positives in the dataset. 
  
Description of Model 2 (Logisitc Regression model with resampled training data): 
  * Accuracy of 99%, indicating this model fits the dataset very well and will predict loan risk very well. 
  * Precision of 92%, meaning 92% of the predicted healthy or low risk borrowers in the retrained dataset were predicted correctly. 
  * Recall of 99%, meaning my model was 95% precise in predicting true positives in the training dataset. 

I would recommend this model due to its high accuracy for the logistic regression using both the original and trained data. Our credit risk report is highly accurate and precise in predicting whether or not a loan borrower is high or low risk. This could be used by banks or loan companies to protect their business while having a relatively reliable model to predict whether the loan borrower will be a risk. 


# Instructions
The instructions for this Challenge are divided into the following subsections:
Split the Data into Training and Testing Sets
Create a Logistic Regression Model with the Original Data
Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

# Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
Generate a confusion matrix.
Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

# Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. 
The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

