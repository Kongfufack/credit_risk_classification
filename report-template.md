# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
Answer: The purpose of this analysis is to use logistic regression model to predict the righ level of loan is high risk or not. 

* Explain what financial information the data was on, and what you needed to predict.
Answer: The data was on the loan status and the loan amount. We needed to predict the risk level of loans.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
Answer: Loan_status : low_risk and high_risk. 

* Describe the stages of the machine learning process you went through as part of this analysis.
Answer: 
1. Data processing
2. Data splitting
3. Model training
4. Model prediction
5. Model evaluation
6. Data resampling
7. Retrainging the model and Evalution by resampled data

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Answer: LogisticRegression , RandomOverSampler


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
1. Balanced Accuracy Score: 0.95
2. Healthy loans (Class 0):
Precision: 1.00
Recall: 0.99
3. High-risk loans (Class 1):
Precision: 0.85
Recall: 0.91

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
1. Balanced Accuracy Score: 0.99
2. Healthy loans (Class 0):
Precision: 1.00
Recall: 0.99
4. High-risk loans (Class 1):
Precision: 0.84
Recall: 0.99

## Summary
根据之前的所有代码，用中文和应该各回答一遍下面的问题：

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Answer: Model 2 with oversampled data seems to perform best. Because the balanced accuracy score is higher than model 1, which means the prediction is more accurate.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Answer: It is more important to predict the 1's, because we want to know the high risk loansm, so `1`'s is better.

If you do not recommend any of the models, please justify your reasoning.
