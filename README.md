# Credit_Risk_Analysis

## Overview of the Analysis
The purpose of this project is to compare two machine learning models to predict credit risk. Depending on the outcome of the models it will then be suggested whether they will be good to use to predict credit risk. 

## Results
The Naive Oversampling Results:
* Balanced accuracy 64%
* Precision for high risk has low positivity at 1%
* Recall Score 64%

SMOTE oversampling Results:
* Balanced accuracy 66%
* Precision for high risk loans 1%
* Recall Score 66% overall

Undersampling Results:
* Balanced accuracy 44%
* Precision for high risk loans 1%
* Recall Score 44% overall

Combination(over and undersampling) Results:
* Balanced accuracy 54%
* Precision for high risk loans 1%
* Recall Score 54% overall

Balanced Random Forest Classifier Results:
* Balanced accuracy 91%
* Precision for high risk loans 4%
* Recall Score 91% overall

Easy Ensemble AdaBoost Classifier Results:
* Balanced accuracy 94%
* Precision for high risk loans 7%
* Recall Score 94% overall

## Summary
We undersampled, oversampled and did a combination of both to try and determine which model is best at predicting which loans are the highest risk. This was done in the first four models. The last two models the data was resampled using ensamble classifiers to try and predict high or low risk loans. The accuracy score is much higher in the last two models. Based on these results, I would recommend using the Easy ensemble. It had the best scores for all three. 
 
