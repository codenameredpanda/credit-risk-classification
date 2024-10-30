# credit-risk-classification

## Overview of the Analysis

This ananlysis examines a dataset of peer-to-peer lending. The purpose of this is to create a model which can identify the credit worthiness of loan applicants for a bank. This model was created using the bank's historical data. Within the data, the categories were: loan size, interest rate, income of the borrower, debt to income ratio, number of accounts, number of derogatory marks, total debt, and loan status. The end goal is for the bank to accurately predict the borrowers loan risk.
The data was split into training and testing data. The logistic regression model was used and the predictions were saved. These predictions were then analysed using the confusion matrix and classification report.

## Results

* Machine Learning Model 1:
    * Accuracy: 99%
    * Overall precision: 92%
        * Healthy loans: 100%
        * High-Risk loans: 85%
    * Overall recall: 95%
        * Healthy loans: 99%
        * High-Risk loans: 91%

## Summary

In summary, this model is an excellent source for the bank to utilize to determine risk. Although the high-risk loan precision was lower than the healthy loan score, at 85% it is still an excellent model for prediction. Considering that healthy loans socred so high, there will be plenty of time for the bankers to personally analyse the 15% of high-risk applicants instead of spending unnecessary time on every single application, thus allowing the bank to focus their efforts on the more important high-risk loans. 
