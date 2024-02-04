# Credit_Risk_Classification

Overview of the Analysis

In this project, the analysis focused on building and evaluating machine learning models to predict credit risk using historical lending data from a peer-to-peer lending services company. The main objective was to identify the creditworthiness of borrowers based on various financial features.

Purpose of the Analysis

* Objective: Build and evaluate machine learning models to predict credit risk.
* Data Source: Historical lending data from a peer-to-peer lending services company.
* Prediction Target: Determine whether a loan is healthy (label 0) or high-risk (label 1).

Data Description

The dataset, sourced from the "lending_data.csv" file, included information on loan status (loan_status) and other relevant financial variables. The goal was to predict whether a loan is healthy (label 0) or high-risk (label 1).

Machine Learning Process

The analysis involved the following stages:

1. Data Preprocessing: The data was read, labels (y) were created from the "loan_status" column, and features (X) from the remaining columns. The data was then split into training and testing sets using train_test_split.
2. Logistic Regression Model: A logistic regression model was implemented using the training data (X_train and y_train). The model's performance was evaluated on the testing data, including generating a confusion matrix and printing a classification report.

Results

Machine Learning Model 1: Logistic Regression
* Accuracy: 99%
* Precision (Label 0 - Healthy Loan): 1.00
* Recall (Label 0): 0.99
* F1-Score (Label 0): 1.00
* Precision (Label 1 - High-Risk Loan): 0.85
* Recall (Label 1): 0.91
* F1-Score (Label 1): 0.88

Machine Learning Model 2: Logistic Regression
* Accuracy: 99%
* Precision (Label 0 - Healthy Loan): 1.00
* Recall (Label 0): 0.99
* F1-Score (Label 0): 1.00
* Precision (Label 1 - High-Risk Loan): 0.84
* Recall (Label 1): 0.99
* F1-Score (Label 1): 0.91

Summary

Both machine learning models exhibit high accuracy and well-balanced precision and recall for predicting healthy and high-risk loans. The original logistic regression model performs exceptionally well, achieving 99% accuracy. The oversampled data model, while slightly lower in precision for high-risk loans, still demonstrates very good performance.
