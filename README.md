# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to evaluate the performance of various machine learning methodologies to predict credit card risk.

## Results 
Credit card risk was evaluated using various machine learning algoriths on a credit card dataset from Lending Club, a peer-to-peer lending services company. The data was oversampled using Naive RandomOverSampler and SMOTE, as well as was undersampled using ClusterCentroids. Further, the data was evaluated using a combinatorial approach of over- and under-sampling using the SMOTEENN algorithm. Lastly, ensemble classifiers BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict credit risk. Accuracy, precision, recall (sensitivity), and F1 were evaluated as summmarized below. For further details, screenshots of the analyses are also included below.

### Naive Random Oversampling: 
  -  accuracy: 0.66
  -  precision: 0.01
  -  recall: 0.71
  -  F1: 0.02

### SMOTE Oversampling: 
  - accuracy:0.66
  - precision: 0.01
  - recall: 0.63
  - F1: 0.02

### ClusterCentroids Undersampling:
  - accuracy: 0.66
  - precision: 0.01
  - recall: 0.69
  - F1: 0.01
 
 ### SMOTEENN:
  - accuracy: 0.64
  - precision: 0.01
  - recall: 0.72
  - F1: 0.02

### BalancedRandomForestClassifier:
  - accuracy: 0.88
  - precision: 0.03
  - recall: 0.67
  - F1: 0.06

### EasyEnsemble Classifier
  - accuracy: 0.93
  - precision: 0.07
  - recall: 0.92
  - F1: 0.13

#### Random Over Sampler 

![image](https://user-images.githubusercontent.com/94587007/163736289-9d3f6a05-08f5-44a9-a8bc-07f7a73001d5.png)


#### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/94587007/163736314-0ff8b6e3-eb29-4621-a0b1-f92f60b57ac9.png)


#### Cluster Centroids Undersampling

![image](https://user-images.githubusercontent.com/94587007/163736332-1f285aa1-3366-45f5-9259-2d3a12c4d530.png)


#### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/94587007/163736365-3e0bcd50-90a1-4c2f-84c5-d39e89a70ab7.png)


#### Easy Ensemble Classifier

![image](https://user-images.githubusercontent.com/94587007/163736388-d3a7ab61-8eba-4517-a571-d64486a9d44a.png)


## Summary
A review of the six models indicates that the EasyEnsembleClassifier model yielded the best results with an accuracy of 93% and a precision of 7% when predicting high-risk credit candidates. The sensitivity rate, or recall, was also the highest out of all the models at 92%. As such, this model is recommended for future similar analyses. 
