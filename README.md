# Module-12-Challenge
Module 12 Challenge

## Overview of the Analysis

The purpose of this analysis was to evaluate a lending services company with machine learning. The data in the CSV was evaluated, trained and tested to see the risk of various borrowers. 
In the CSV, we can see the size of the loan, borrower income, number of accounts, derogatory marks, total debt, loan status etc.
The amount of healthy loans did outweigh the number of high risk loans in this data set, this shows that the data set is oversampled.
The goal of this analysis is to make a model to accurately predict if a loan is healthy or high risk.
In the process of making this model, we need to split the data into training and testing sets, create a logistic regression model with the data from the CSV, predict a logistic regression model with the training data, create a model with resampled data and then use that to predict a logistic regression model. Once all this is done, we must analyze and compare the results.

## Results

* Machine Learning Model 1 (Original Data):
  * Accuracy: 95.2%
  * Precision for 0: 100%
  * Recall for 0: 99%
  * Precision for 1: 85%
  * Recall for 1: 91%
  
![image](https://github.com/nkp1027/Module-12-Challenge/assets/133065472/3d7aa451-4a3b-4f4c-9d5c-468012118448)

* Machine Learning Model 2:
  * Accuracy: 99.4%
  * Precision for 0: 100%
  * Recall for 0: 99%
  * Precision for 1: 84%
  * Precision for 1: 99%
  
![image](https://github.com/nkp1027/Module-12-Challenge/assets/133065472/362b92f2-15e1-4d8e-a4e3-f1915839c4ae)

## Summary

In comparison of the linger regression models whether they were oversampled or the original data, we can appreciate a incread of 4% in accuracy for the second Model. We do lose 1% of precision in the 1 value when we use the oversampled data but we also have a 8% increase in precision in the 1 value for model 2. This is great for the lending services company since this means that the high risk loans will be classified properly. 
The balanced accuracy of model 2 is greater than model 1 which we can conclude model 2 to be the best fit since it will be more precise in classufication of loans.
I recommmend the Model 2 because of this reason.

## Technologies

pandas, numpy, sklearn.metrics, sklearn.linear_model, sklearn.train_test_split, imbalanced-learn, google Colab
