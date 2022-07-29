# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to use different techniques within machine learning to train and evaluate models. We will be comparing all of the models and results to see which is best to evaluate credit risk based off the data that we have received. 

## Results

From lowest to highest accuracy scores, here are the results from each different model. 

### Combination and Undersampling
Combination:
![Combination Over and Under Sampling](https://user-images.githubusercontent.com/100896787/181661829-a3c6eee4-39d9-416f-bc16-712a8ae5dfa5.PNG)
Undersampling:
![Undersampling](https://user-images.githubusercontent.com/100896787/181661834-407e1feb-8e1d-40f8-9870-4e70c56af73d.PNG)

* These two models had the lowest accuracy scores (0.544733) 
* Their precision values were the same
* The combination model had a higher f1 score 

### SMOTE and Oversampling
SMOTE:
![SMOTE Oversampling](https://user-images.githubusercontent.com/100896787/181662213-f387332d-30e9-4a2e-9e44-11284988bb2d.PNG)
Oversampling:
![Random Oversampling](https://user-images.githubusercontent.com/100896787/181662218-e01c3d41-3d2e-46d1-93e1-a1738a92249b.PNG)

* Both of these models had the same accuracy score (0.651376)
* Their precision values are the same
* Even their f1 scores are very similar (the SMOTE model had a higher f1 score under the low_risk category)

## Summary
