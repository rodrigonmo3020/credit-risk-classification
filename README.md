# credit-risk-classification
Repository for challenge 20 files

# Module 20 Report

## Overview of the Analysis
*   This code is made to train and evaluate a model based on loan risk. we will use and analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

*   The dataset displays information like loan size, interest rate, borrower income and total debt ammount that is the most representative information for the analysis.

*   The variable that was aimed to predict was the Loan status that states if a loan is a high risk or a lower risk according to the complemetary information given on the dataset.

*   We went through bellow machine learning process as part of this analysis:
    * 1- Read and display the data
    * 2- Split data into labels and features
    * 3- Split the data into training a testing datasets using the function train_test_split
    * 4- Fit a logistic regression model by using the training data
    * 5- Make a prediction of the labels using the testing data.
    * 6- Evaluate the model’s performance by generating an accuracy score, confusion matrix and a classification report.

## Results
* Machine Learning Model: Logistic Regression
    * Accuracy: 99% 
    * Precision: (0) 100% | (1) 85%
    * Recall: (0) 99% | (1) 91%

## Summary
*   Acording to the classification report, the logistic regression model has a very high Accuracy performance and predict very well the label `0` (healthy loan), however for the label `1` (high-risk loan) the precision and the f1-score has a lower Accuracy performance and this autcome matches with the results of the confusion matrix so probably we will need to look for another training model to evaluate wether its possible to get better predictions with this dataset for the label `1` (high-risk loan), which is the most critical factor to make a loan decision, or if additional infromation is needed on the dataset.