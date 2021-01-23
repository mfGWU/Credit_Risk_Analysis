# Deliverable 17 Written Analysis


# Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to apply data preparation, statistical reasoning and machine learning (ML) algorithms to solve a real-world challenge like credit card risk.  Credit card risk can be classified as a good loan or a risky loan which is appropriate training, building and evaluating imbalanced-learn and scikit-learn libraries using resampling.  The dataset from LendingClub will be oversampled using RandomOverSampler and SMOTE algorithm.  As well as combinatorial approach of over- and undersampling using the SMOTEEN algorithm. Finally compare two new ML models to reduce bias leveraging BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms to predict credit risk.

# Results: 

* RandomOverSampler – Oversampling
* Accuracy: 66.0%
*![ RandomOverSample](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "RandomOverSample")


* SMOTE – Oversampling
* Accuracy: 65%
*![ SMOTE](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "SMOTE ")


* ClusterCentroids – ClusterCentroids
* Accuracy: 65%
*![ ClusterCentroids](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png " ClusterCentroids ")


* SMOTEENN - Combination (Over and Under)
* Accuracy: 53%
*![ SMOTEENN](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png " SMOTEENN ")


* RandomForestClassifier - Balanced Random Forest Classifier
* Accuracy: 99.6%
*![ RandomForestClassifier](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png " RandomForestClassifier ")

* AdaBoostClassifier - Easy Ensemble AdaBoost Classifier
* Accuracy: 99.6%
* ![ AdaBoostClassifier](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png " AdaBoostClassifier ")


# Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

