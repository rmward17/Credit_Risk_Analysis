# Credit_Risk_Analysis
## Overview 
The purpose of this analysis is to predict credit risk based on loan data from 2019. To do so, we fit multiple supervised machine learning models with a variety of sampling techniques in order to find the best one.

We tested 2 oversampling algorithms (one naive oversampling algorithm and a SMOTE algorithm), an undersampling algorithm, a combination algorithm, and 2 ensemble alogrithms (a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost Classifier)

## Results:
- Naive Oversampling ALgorithm
  - Accuracy Score: 0.62
  - Precision Score: 0.99
  - Recall Score: 0.63
- SMOTE Algorithm
  - Accuracy Score: 0.62
  - Precision Score: 0.99
  - Recall Score: 0.65
- Undersampling Algorithm
  - Accuracy Score: 0.62
  - Precision Score: 0.99
  - Recall Score: 0.57
- Combination Algorithm
  - Accuracy Score: 0.54
  - Precision Score: 0.99
  - Recall Score: 0.58
- Balanced Random Forest Classifier
  - Accuracy Score: 0.92
  - Precision Score: 0.99
  - Recall Score: 0.92
- Easy Ensemble AdaBoost Classifier
  - Accuracy Score: 0.94
  - Precision Score: 0.99
  - Recall Score: 0.94

## Summary:
Based on the results above, we can see that the ensemble models have much better accuracy scores than the other four. All six models have very good percision scores but there is more variety amongst the recall scores.This means that wiht all of these models, those who are deemed a high risk are most likely to actually be high risk. However, the ensemble models are better at making sure those who are high risk were accurately flagged.

Based on all of the scores, I would reccoemned either of the ensemble models. They do an exceptional job at correctly flagging high risk applicants.
