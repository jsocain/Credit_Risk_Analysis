# Credit_Risk_Analysis

## Overview of the analysis: 
Using machine learning and credit card credit dataset, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results: 

![Algorithm_Table](images/algorithm_table2.png)

- none of the resampling models used performed very well 
- the under sampling model, ClusterCentroids, performed the worst of all models tested
- both ensemble classifers performed significantly better
- the EasyEnsembleClassifier performed the best 

## Summary:

Due to the high balanced accuracy score of .925 plus the highest recall score of .94, the EasyEnsembleClassifier outperformed all other machine leaning algorithms tested and should be the algoriths used to predict credit risk.