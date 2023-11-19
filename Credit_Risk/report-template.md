# Module 12 Report Template

## Overview of the Analysis

* The purpose of the analysis is to build a machine leaning model that predicts the creditworthiness of borrowers based on a dataset of historical lending activity.
* The financial information in the dataset includes the amount of the loan, corresponding interest rates, and relevant information about lenders such as income and the ratio of the debt to the income etc. The target variable for prediction is the loan status, presenting whether a loan is categorized as healthy or high-rick.
* The loan_status variable is distributed with a count og 75,036 for the value 0, indicating healthy loans, and a count of 2,500 for the value 1, indicating high-risk loans.
* The stages of the machine learning process I went through involved data loading, data splitting, model building (including fitting, prediction, and evaluation) using the original data, data resampling, and  model building using the resampling data.  
* In this analysis, the LogisticRegression method was employed to create model, and the RandomOverSampler technique was utilized to address class imbalance in the original data.

## Results

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
