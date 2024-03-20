# Credit Risk Classification Report

## Overview of the Analysis

* This challenge uses a dataset of historical lending activity from a peer-to-peer lending services company. A logistic regression model and various techniques were used to train and evaluation the data to ultimately identify the creditworthiness of borrows.  

* The model evaluates the `loan_status`, identified as `0` for healthy and `1` for high-risk. 

* The labels set (y) was created from the `loan_status` column, and the features (X) from the remaining columns. The data was then split into training and testing datasets. The logistic regression model was then created and fit with the training dataset. Predictions were made using the testing dataset. A confusion matrix and a classification report are provided to display the results. 


## Results

* Machine Learning Model - Logistic Regression:
    * The model was able to predict all results with 99% accuracy. 
    * With regards to precision, the model was able to correctly predict 100% of the healthy loan labels and 87% of the high-risk label.
    * Recall scores indicated that the model was able to correctly predict 100% of the healthy loan labels and 89% of the high-risk loan labels.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* I recommend the use of this machine learning model given the high precision and recall values for high-risk loan labels at 87% and 89%, respectively. This means that of all the instances that were predicted by the model as high-risk, 87% of loans were actually high-risk. Furthermore, of all of the high-risk loans that were truly high-risk, the model was able to correctly identify 89% of them as high-risk.

* Evaluation of this model's effectiveness in determining the high-risk loan label is more important given that it was able to accurately predict 100% of the healthy loan labels. Additionally, a high-risk loan status will allow the financial institution to deny loans to individuals deemed unlikely to repay. 


