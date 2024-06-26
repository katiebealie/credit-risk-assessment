# Credit Risk Assessment

## Overview of the Analysis

The purpose of this analysis was to use supervised learning methods to train a machine learning algorithm. This analysis used a logistic regression model to assess the risk level of various loans and generate predictions. 
* Process:
    * loan_status variable split from dimensions, loan_status values saved as label array
    * dataframe with remaining data designated as x dataset of features
    * train-test-split used to divvy up data for training and testing
    * logistic regression used regularize x features and separate them into two classes
    * model is instantiated, fit, run against tet data
    * confusion matrix and classifcation report generated for analysis


## Results

* Logistic Regression Model:
    * Accuracy: 99%
    * Precision for healthy loans: 100%
    * Precision for high risk loans: 87%
    * Recall for healthy loans: 100%
    * Recall for high risk loans: 89%

