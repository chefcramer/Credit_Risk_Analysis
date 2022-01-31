# Credit_Risk_Analysis
Module 17, Supervised Machine Learning and Credit Risk
## Overview of Analysis
This project was to use machie learning to predict credit card risk, a safe loan vs an unsafe. We used 6 machine learning models to examine this data, RandomOverSampling, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data was oversampled using the RandomOverSampler and SMOTE algorithms, and the data was then undersampled using the ClusterCentroids algorithm. A combination of over- and undersampling using the SMOTEENN algorithm. Two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results
The balanced accuracy scores, precision, recall and F1 scores below display the results of the various models for comparison.

### Accuracy Scores 
Accuracy is the percentage of predictions that are correct. This method compares the actual outcome (y) values from the test set against the model's predicted values.
- RandomOverSampling: .644
- SMOTE: .651
- ClusterCentroids: .529
- SMOTEENN: .644
- BalancedRandomForestClassifier: .787
- EasyEnsembleClassifier: .925

### Precision Scores
Precision is a measure of how reliable a positive classification is.
- RandomOverSampling: .99
- SMOTE: .99
- ClusterCentroids: .99
- SMOTEENN: .99
- BalancedRandomForestClassifier: .99
- EasyEnsembleClassifier: .99

### Recall (Sensitivity) 
A test with high sensitivity (recall) means few false negatives, though there may be a high number of false positives. Recall is the ability of the classifier to find all the positive samples.
- RandomOverSampling: .57
- SMOTE: .66
- ClusterCentroids: .45
- SMOTEENN: .57
- BalancedRandomForestClassifier: .91
- EasyEnsembleClassifier: .94

### F1 
The F1 score is a combination statistic of precision and recall. A pronounced imbalance between sensitivity and precision will yield a low F1 score.
- RandomOverSampling: .72
- SMOTE: .79
- ClusterCentroids: .62
- SMOTEENN: .72
- BalancedRandomForestClassifier: .95
- EasyEnsembleClassifier: .97

### Imbalanced Classification Reports
- RandomOverSampling
![random](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/random_oversample.PNG)

- SMOTE
![SMOTE](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/SMOTE.PNG)

- ClusterCentroids
![CC](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/cluster_centroid.PNG)

- SMOTEENN
![SMOTEENN](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/SMOTEEN.PNG)

- BalancedRandomForestClassifier
![BRFC](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/random_forest.PNG)

- EasyEnsembleClassifier
![EEC](https://github.com/chefcramer/Credit_Risk_Analysis/blob/main/resources/EEC.PNG)

## Summary
The EasyEnsembleClassifier is the CLEAR winner in this examination of the data. It has an accuraccy score of 93%, a precision score of 99%, a Sensitivity score of 94%, and a F1 score of 97%. This is by far the most accurate predictor of the data.
