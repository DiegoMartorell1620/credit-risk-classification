# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting healthy and high risk loans. Also, assess it's accuracy and possibly provide support in loan classification tasks.

* Explain what financial information the data was on, and what you needed to predict.

The data was based on loan size, interest rate, borrower income, ratio of debt to income, number of accounts, derogatory marks and total debt.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

True positives, false positives, false negatives, true negatives, total number of predictions, recall , precision.

* Describe the stages of the machine learning process you went through as part of this analysis.

Data preparation - When creating the X and y variables

Data Splitting - When creating the training and testing sets

Model training- When I used the regression model

Model Evaluation- When I used a confusion matrix

Performance Analysis - When I analyzed the results of the confusion matrix


* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

Logistic Regression 
Confusion Matrix

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

For healthy loans:

True Positives= 18663

False Positives=102

False Negatives=56

True Negatives=563

Precision=99.46%

Recall=99.7%


For high risk loans:

True positives=563

False positives=102

False Negastives=56

True Negatives=18663

Precision=84.6%

Recall=90.9%


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

I recommend using the model for healthy loans (0's). The reason is simple, the precision and recall are higher. Therefore, it predicts results more accurately.
