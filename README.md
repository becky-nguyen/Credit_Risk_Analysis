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

### Balanced Random Forest
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/100896787/181682938-3738281d-906a-4f92-a148-ce5f31e96d67.PNG)

* This model has a accuracy score of 0.788547
* The average/total precision value remains the same as the previous models 
* The f1 score is higher than all the previous models


### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/100896787/181683088-78c2d9f8-a803-4067-b065-ee770ab3503a.PNG)

* This model has the highest accuracy score (0.931660)
* Its average precision value remains the same as the previous models
* The f1 score is the highest of all the values 

## Summary
The balanced accuracy score is a metric that is used the assesss the performance of a model. It is ranged from 0 and 1, with 1 being the best performance. Of the 6 models that we tested, I would recommend the Easy Ensemble AdaBoost Classifier as it had a high accuracy score of 0.931660. Not only that, but it had the highest recall score (which represents the model's ability to correctly predict positives out of actual positives). I would not recommend the combination and undersampling models, as those had very low scores of 0.544733. It would be bad to ue a model like that to test for credit risk. 
