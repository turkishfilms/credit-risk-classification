# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results
This analysis was performed in order to identify high_risk or healthy loans, based on other financial criteria. These criteria included: 
Loan size
Interest rate
Borrower income
Debt to income ratio
Number of accounts
Derogatory marks
Total debt.
Our goal was to use these indicators to predict the risk associated with these loans with an accuracy of 94% or better. We chose Logistic regression models for this task, and decided to run two tests, with seperate training datasets as well as with resampled data. To start the training process data must first be collected and cleaned, after this step we fed the data into a test/training data splitter and procceeded to run Linear regressions using a fixed random seed. To generate the reports we used several functions included in SKLearn to create confusion matrices, and ultimaely geerate accuracy scores for our two models.

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
