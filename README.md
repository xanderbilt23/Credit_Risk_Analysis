# Credit_Risk_Analysis

## Overview

Used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Used the credit card credit dataset from LendingClub, a peer-to-peer lending services company, then oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and to evaluate the performance of these models. 

## Results 

# Naive Random Oversampling

- Balanced accuracy score: 66%
- High risk precision is low at 1% with a recall of 72% recall
- Low risk precision is 100% with a recall of 60%

![Naive_Random_Oversampling]()

![Naive_Random_Oversampling_Pre]()

# SMOTE Oversampling

- Balanced accuracy score: 65%
- High risk precision is low at 1% with a recall of 61% recall
- Low risk precision is 100% with a recall of 70%

![SMOTE_Oversampling]()

![SMOTE_Oversampling_pre]()

# Undersampling with ClusterCentroids resampler

- Balanced accuracy score: 65%
- High risk precision is low at 1% with a recall of 69% recall
- Low risk precision is 100% with a recall of 40%

![ClusterCentroids]()
![ClusterCentroids_pre] ()

# Combination (Over and Under) Sampling

- Balanced accuracy score: 54%
- High risk precision is low at 1% with a recall of 72% recall
- Low risk precision is 100% with a recall of 57%

![Over_and_Under]()
![Over_and_Under_pre]()

# Balanced Random Forest Classifier

- Balanced accuracy score: 77%
- High risk precision is low at 3% with a recall of 65% recall
- Low risk precision is 100% with a recall of 89%

![Random Forest]()
![Random Forest_pre]()

# Easy Ensemble AdaBoost Classifier

- Balanced accuracy score: 93%
- High risk precision is low at 9% with a recall of 92% recall
- Low risk precision is 100% with a recall of 94%

![Ensemble AdaBoost]()
![Ensemble AdaBoost_pre]()

## Summary 


In the Naive Random Oversampling, SMOTE Oversampling, Undersampling with ClusterCentroids resampler, & Combination (Over and Under) Sampling models there is a low balanced accuracy score seen in all models when compared to the ensemble models: Balanced Random Forest Classifier & Easy Ensemble AdaBoost Classifier. Also they all have lower high risk precisions when compared to the two ensemble models. Based off this it is recommended to use the Easy Ensemble AdaBoost Classifier as it is the most accurate model. 