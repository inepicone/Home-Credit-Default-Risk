# Home-Credit-Default-Risk
Creating a complete pipeline to preprocess the data, train the model and make predictions for the Home Credit Default Risk Kaggle competition.

## Introduction

Kaggle is a web platform and community for data scientist and machine learning engineers where competetitions and datasets are regularly published.

This particular competition is a binary Classification task: we want to predict whether the person applying for a home credit will be able to repay its debt or not. The competition finished 4 years ago, so you will find a lot of blog posts and code written for it, we encourage you to read everything you can about it.

The dataset is composed of multiple files with different information about loands taken. In this project we're going to exclusively work with the main files: application_train.csv and application_test.csv.

The competition uses [Area Under the ROC Curve](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc?hl=es_419) as the evaluation metric, so our models will have to return the probabilities that a loan is not paid for each row.

## Overview:
    - EDA and Correlation analysis.
    - Data Preprocessing
    - Models Used:
        LogisticRegression
        + GridSearch to improove the performance.
        Random Forest Classifier
        LGBM
    - Pipeline incorporation
    
