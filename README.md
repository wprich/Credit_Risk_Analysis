# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to help a client determine credit risk out of a population.  This uses numerous machine learning methodologies and different sampling techniques to test the models generated.  The main target was the 'loan_status' column out of the initial data set as that column indicated that the previous model that was used determined if that borrower was a high or low risk for the creditor.  By isolating this target and testing different variables against it in different types of models, we could see whether the previous model was valid or could be improved upon.

## Results

There were seven different models generated and tested after the data was split.  Screenshots of their summarys will be given below along with what type of sampling/model was used:

Naive Random Sampling
![Naive Random Sampling](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/Naive_Random_Sampling.png)


SMOTE Oversampling

![SMOTE Oversampling](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png)


Cluster Centroids Undersampling

![Cluster Centroids Undersampling](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/ClusterCentroids_Undersampling.png)


Combination

![Combination](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/Combination.png)


SMOTEENN

![SMOTEENN](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png)


Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/Balanced_RFC.png)


Easy Ensemble Classifier

![Easy Ensemble Classifier](https://github.com/wprich/Credit_Risk_Analysis/blob/main/Images/Easy_Ensemble_Classifier.png)

## Summary

These models were useful in determing the accuracy of the previous determination of the initial dataset.  The average precision across each model was 0.99.  This indicates that the previous datasets accuracy was around 99%.  This tells us that 99% of the time, its classification of a borrower being high or low risk was accurate given all factors.  This model is ideal and no recommendations can be given at this time.
