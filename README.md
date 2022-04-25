# Credit_Risk_Analysis
## Overview of the analysis:
The purpose of this analysis is credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once done, I’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 
* Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. 







* ![Naive_random-OS](https://user-images.githubusercontent.com/93004710/164803712-16f3824c-eaf9-4ca8-bbd0-9595bfab2cdc.png)










* Naive Random Oversampling chart above shows a balanced accuracy score of 64% and recall score for high risk 62% and low risk 65%.









* ![smote-oversampling](https://user-images.githubusercontent.com/93004710/164803730-52a6914b-98d9-4de3-bd80-0872475283e3.png)











* SMOTE Oversampling chart above shows a balanced accuracy score of 63% and recall score for high risk 62% and low risk 654%.








* ![Undersampling](https://user-images.githubusercontent.com/93004710/164803744-97853594-8dcd-413d-a055-3c27cd2b2450.png)







* Undersampling chart above shows a balanced accuracy score of 53% and recall score for high risk 61% and low risk 45%.







* ![easy-ensemble-adaboost](https://user-images.githubusercontent.com/93004710/164803792-9a29e585-bf53-4fb4-bc02-99649518dff9.png)







* Easy-Ensemble AdaBooat Classifier chart above shows a balanced accuracy score of 93% and recall score for high risk 91% and low risk 94%.





* ![combination-sampling](https://user-images.githubusercontent.com/93004710/164803880-6a4a8a31-8b0b-47e7-be3f-e14d60975be3.png)





* Combination sampling (SMOTEENN) chart above shows a balanced accuracy score of 63% and recall score for high risk 71% and low risk 55%.




* ![Balanced-randomForest](https://user-images.githubusercontent.com/93004710/164803933-763844d9-dbea-4ce4-802b-6f3f9a848b52.png)




* Balanced Random Forest Classifier chart above shows a balanced accuracy score of 80% and recall score for high risk 71% and low risk 88%.



## Summary: 
*  After reviewing thr machine learning model results it is clear the ensemble models have higher accuracy scores. I recommend using the model with the highest accuracy score, the easy-ensemble-adaboost classifier model.
