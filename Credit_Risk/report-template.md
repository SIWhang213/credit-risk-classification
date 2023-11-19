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
  * Accuracy: 99%
  * Precision (Class 0): 100%
  * Precision (Class 1): 87%
  * Recall (Class 0): 100%
  * Recall (Class 1): 89%
  * F1-Score (Class 0): 100%
  * F1-Score (Class 1): 88%

* Machine Learning Model 2:
  * Accuracy: 100%
  * Precision (Class 0): 100%
  * Precision (Class 1): 87%
  * Recall (Class 0): 100%
  * Recall (Class 1): 100%
  * F1-Score (Class 0): 100%
  * F1-Score (Class 1): 93%

## Summary
The results indicate that both machine learning models perform well in terms of accuracy, precision, recall, and F1-Score fot Class 0. However, Model 2 exhibits slightly better performance, especially in terms of recall for Class 1. Model 2 achieves a perfect recall of 100% for Class 1 (high-risk loans), whereas Model 1 achieves 89% recall for the same class. Essentially, Model 2 accurately identifies all instances of high-risk loans without any false negatives for Class 1. Therefore, if it is crucial to accurately identify high-risk loans to minimize financial risk, Model 2 is the recommended choice.
However, both Model 1 and Model 2 achieve a precision of 87 % for Class 1. This implies that there is a 13 % proportion of loans predicted as high-risk that are actually healthy. Incorrectly categorizing a healthy loan as high-risk poses potential challenges in terms of customer trust and reputational consequences. The loss of customers or credibility can have lasting impacts on long-term profitability. As a result, there is room for improvement in minimizing such misclassifications to enhance trust and fortify the institution's reputation, ultimately contributing to sustained profitability.
