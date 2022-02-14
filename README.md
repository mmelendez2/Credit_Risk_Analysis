# -Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
The purpose of this analysis is to oversample credit card credit data from LendingClub using a few different machine learning algorithms. We'll use **RandomOverSampler** and **SMOTE** algorithms and also undersample the data using **ClusterCentroids** algorithms. After this, we'll use a combinatorial approach of over- and undersampling using the **SMOTEENN** algorithm. Finally, we'll compare two other machine learning models that reduce bias - **BalancedRandomForestClassifier** amd **EasyEnsembleClassifier**, to predict credit risk. Once we're finished, we'll evaluate the performance of these six models and provide a recommendataion on whether they should be used to predict credit risk.

## Results:

### Model 1 - RandomOverSampler

![image](https://user-images.githubusercontent.com/89496798/153797531-e131c035-94ac-42eb-a77c-aaba05a69d2e.png)

- Balanced Accuracy Score - 0.6293939430565123
- Precision Score (High Risk) - 0.01
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.57
- Recall Score (Low Risk) - 0.68
- Recall Score (Average) - 0.68

### Model 2 - SMOTE

![image](https://user-images.githubusercontent.com/89496798/153797858-71e67c5e-7336-4524-b909-ad9f662301a9.png)

- Balanced Accuracy Score - 0.6293939430565123
- Precision Score (High Risk) - 0.01
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.57
- Recall Score (Low Risk) - 0.68
- Recall Score (Average) - 0.68

### Model 3 - ClusterCentroids (Undersampling)

![image](https://user-images.githubusercontent.com/89496798/153797990-b4a88035-2489-47ee-8499-c09e06312286.png)

- Balanced Accuracy Score - 0.6293939430565123
- Precision Score (High Risk) - 0.01
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.57
- Recall Score (Low Risk) - 0.47
- Recall Score (Average) - 0.47

### Model 4 - SMOTEENN (Over- & Undersampling)

Summary:

![image](https://user-images.githubusercontent.com/89496798/153798075-318d9bcd-548c-4d2c-9561-fc5d67a88e1f.png)

- Balanced Accuracy Score - 0.5198601190116473
- Precision Score (High Risk) - 0.01
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.70
- Recall Score (Low Risk) - 0.58
- Recall Score (Average) - 0.58

### Model 5 - Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/89496798/153798169-ebeb59ec-35c4-4720-9f22-26eb42eba9ab.png)

- Balanced Accuracy Score - 0.7877672625306695
- Precision Score (High Risk) - 0.04
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.67
- Recall Score (Low Risk) - 0.91
- Recall Score (Average) - 0.91

### Model 6 - Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/89496798/153798261-48077cc6-5417-41e4-9d5c-6f5bbd613492.png)

- Balanced Accuracy Score - 0.925427358175101
- Precision Score (High Risk) - 0.07
- Precision Score (Low Risk) - 1.00
- Precision Score (Average) - 0.99
- Recall Score (High Risk) - 0.91
- Recall Score (Low Risk) - 0.94
- Recall Score (Average) - 0.94

## Summary
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
