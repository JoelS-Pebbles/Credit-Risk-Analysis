# Credit-Risk-Analysis

## Overview
Applied machine learning to solve credit card risk. Employed techniques to train and evaluate models with unbalanced classes. Sampled datawith RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Used the combinational approach of oversampling and undersampling using SMOTEENIN. Copmared the two machine learning models that reduce bias, BlanaceRandomForestClassifier and EasyEnsembleClassifier, to predict credit card risk. 

# Results
In the tables below there is a comparison of the outputs of the machine learning models. 

*The accuracy scores and recal scores have different sampling methods. SMOTE oversampling has the combo of good scores with an accuracy of 65% and sensitivity of 68%. The remaining sampling methods might be a little higher in accuracy but much lower when it comes to recall percentage. 
*These results show that the two Ensemble Classifiers, random forest and ensemble adaboost are the two best methods to work with when using this dataset. Both have better accuracy, average recall and are effective with recall for situations with low risk. 

![smote over](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/smote%20over.PNG)
![random oversampling](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/random%20oversampling.PNG)
![cluster centroids](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/cluster%20centroids.PNG)
![smoteenn combo over and under](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/smoteenn%20combo%20over%20and%20under.PNG)
![adaboost classsifier](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/adaboost%20classsifier.PNG)
![random forest classifier](https://github.com/JoelS-Pebbles/Credit-Risk-Analysis/blob/main/random%20forest%20classifier.PNG)

## Summary
The F1 score in terms of a combonation score of percision and recall gives another important metric. The F1 score for SMOTE oversampling is 81% which is the best methog among the other four sampling methods. Including the comparison of the ensemble classifier methods, each has an F1 score of 1 and makes these two methods better overall. The recommended choice is the Easy Ensemble Adaboost Classifier because this model has the best overall scores in this comparison of the six models. 
