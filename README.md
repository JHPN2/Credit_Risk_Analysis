# Credit Risk Analysis
## Overview
Using the provided credit card credit dataset from LendingClub, we are tasked to perform of all the machine learning models outlined in this module. These include oversampling the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. In addition we'll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, we'll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. We'll be using the results to evaluate the performance of these models and write a recommendation on whether they should be used to predict credit card risk.

## Results
### Oversampling:
* **Naive Random**: Based on the results, our calulated **Balanced Accuracy** Score was 64.1%. The *High Risk* **Precision** and **Recall** scores were 1% and 60%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 68%.


* **SMOTE Algorithm**: Based on the results, our calulated **Balanced Accuracy** Score was 63.7%. The *High Risk* **Precision** and **Recall** scores were 1% and 60%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 68%.


### Undersampling
* **Cluster Centroids**: Based on the results, our calulated **Balanced Accuracy** Score was 52.9%. The *High Risk* **Precision** and **Recall** scores were 1% and 61%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 45%.


* **SMOTEENN Algorithm**: Based on the results, our calulated **Balanced Accuracy** Score was 62.4%. The *High Risk* **Precision** and **Recall** scores were 1% and 70%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 55%.


### Ensemble Learners:
* **Balanced Random Forest Classifier**: Based on the results, our calulated **Balanced Accuracy** Score was 78.8%. The *High Risk* **Precision** and **Recall** scores were 4% and 67%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 91%.


* **Easy Ensemble AdaBoost Classifier**: Based on the results, our calulated **Balanced Accuracy** Score was 92.5%. The *High Risk* **Precision** and **Recall** scores were 7% and 91%. While the *Low Risk* **Precision** and **Recall** scores were 100% and 94%.

## Summary
