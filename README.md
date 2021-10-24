# Credit_Risk_Analysis_Challenge

## Overview
Purpose of this challenge was to predict credit risk using the machine learning model learned in this module. This module walked through several methods to run these predictions, such as: SMOTE oversampling, SMOTEENN sampling, Easy Ensemble Classifying, etc. Each method produced classification reports and confusion matrices to compute overall risk values.

## Results

**Naive Random Oversampling**
- Accuracy Score: 66.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 66%
- Recall Low Risk: 67%

**SMOTE Oversampling**
- Accuracy Score: 66.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 65%
- Recall Low Risk: 69%

**Undersampling**
- Accuracy Score: 51.2%
- Precision High Risk: 1%
- Precision Low Risk: 99%
- Recall High Risk: 53%
- Recall Low Risk: 50%

**SMOTEENN Analysis**
- Accuracy Score: 63.5%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 60%

**Random Forest Analysis**
- Accuracy Score: 66.6% (the devil....)
- Precision High Risk: 72%
- Precision Low Risk: 100%
- Recall High Risk: 33%
- Recall Low Risk: 100%

**Easy Ensemble Analysis**
- Accuracy Score: 89.9% 
- Precision High Risk: 8%
- Precision Low Risk: 100%
- Recall High Risk: 86%
- Recall Low Risk: 94%

## Summary

In trying to find the most accurate model, it really wasn't even close. The Easy Ensemble Analysis had an accuracy score of 89.9%, and the next highest accuracy was a tie for 66.7%. On this fact alone, I would highly recommend using the Easy Ensemble Analysis method for producting any valuable insights. 
