# Credit Risk Report

## Overview of the Analysis

The purpose of this analysis is to demonstrate whether or not the created model is recommendable when trying to figure out which customers should be given a loan freely or under some level of caution. The model for this task took in data that contained information regarding: loan size, interest rate, borrower income, debt-to-income, number of accounts, derogatory marks, and total debt. These seven features are used to determine if they can predict whether the loan status of the borrower should be either a "healthy loan" or a "high-risk loan". For the dataset, the true labels for loan status were calculated to be 75036 for "healthy loan" and 2500 for "high-risk loan". Upon splitting the dataset into training and testing sets, the "healthy loan" labels were determined to be 56277 for the training set and 18759 for the testing data. The count of "high-risk loan" labels for the training set was 1875 and 625 for the testing set. 

The machine learning process consisted of first splitting the dataset into a training and testing set. The X parameter for the training set contained information about the seven features while the y parameter had information about the loan status. Both the X and y parameters were fit into the Logistic Regression model. This fitted model then predicted the loan status for the testing set data when it was given information about the seven features of the testing data. A confusion matrix and classification report were found based on the predicted and actual loan status values.


## Results

* Logistic Regression Model:
    * Accuracy: 99%
    * Precision for Healthy Loans: 100%
    * Precision for High-Risk Loans: 87%
    * Recall for Healthy Loans: 100%
    * Recall for High-Risk Loans: 95% 


## Summary

The accuracy of the model was calculated to be 99%. While this may seem to indicate that the model is performing excellently, there is one factor to consider before making this conclusion: there is more data about healthy loans than high-risk loans, so the model will be better at predicting healthy loans than it will at predicting high-risk loans. With that said, the large values of the precision and recall for high-risk loans indicates that the model still does a good job at predicting when to say the loan status should be classified as "high-risk". For this reason, this model should be recommended when determining the loan status of borrowers.  

