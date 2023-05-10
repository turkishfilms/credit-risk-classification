# Module 12 Report Template

## Overview of the Analysis

## Results
This analysis was performed in order to identify high_risk or healthy loans, based on other financial criteria. These criteria included: 
- Loan size
- Interest rate
- Borrower income
- Debt to income ratio
- Number of accounts
- Derogatory marks
- Total debt.
Our goal was to use these indicators to predict the risk associated with these loans with an accuracy of 94% or better. We chose Logistic regression models for this task, and decided to run two tests, with seperate training datasets as well as with resampled data. To start the training process data must first be collected and cleaned, after this step we fed the data into a test/training data splitter and procceeded to run Linear regressions using a fixed random seed. To generate the reports we used several functions included in SKLearn to create confusion matrices, and ultimaely geerate accuracy scores for our two models.


-Precision is a measure of the amount of True Positive results the model correctly identifies amidst the positives the model predicted. 
  This number's importance scales with the cost of false positives. 

-Recall is a measure of the amount of True Positive results the model correctly identifies amidst the positives in the data. 
  This number's importance scales with the cost of false negatives. 

* Machine Learning Model 1:
  * Balanced Accuracy Score: 95.2% (measure of performance over each label type, aggregated) 
  * Healthy Loan Precision: 1.00
  * High-Risk Loan Precision: 0.85
  * Weighted avg Precision: 0.99
  * Healthy Loan Recall: 0.99
  * High-Risk Loan Recall: 0.91
  * Weighted avg Recall: 0.99

* Machine Learning Model 2:
  * Balanced Accuracy Score: 99.3% (measure of performance over each label type, aggregated) 
  * Healthy Loan Precision: 1.00
  * High-Risk Loan Precision: 0.84
  * Weighted avg Precision: 0.99
  * Healthy Loan Recall: 0.99
  * High-Risk Loan Recall: 0.99
  * Weighted avg Recall: 0.99

## Summary

Both models have fairly high precision and accuracy scores. I would recommend the logistic regression model using resampled data as its balanced accuracy score is high by over 3 percent. There are tradeoffs between model 1's high High Risk Loan Precision score and Model 2's High Risk loan Recall, but after its all averaged out, Model 2 is superior.  
Accurately predict healthy loans is very important for the success of these models, and both perform exceptionally well. 

