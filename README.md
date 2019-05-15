# MPP Data Science Final Project

## Overview

The [Microsoft Professional Program in Data Science](https://www.edx.org/microsoft-professional-program-data-science) final project was to analyse and predict loan applications as to whether they will be successful or not using US Government data.


## Background

The Home Mortgage Disclosure Act (HMDA) was enacted by Congress in 1975 and requires financial institutions like banks, savings associations, credit unions, and other mortgage lending institutions to report information about all of the loan applications they receive. In 2011, the authority for this reporting was transferred to the Consumer Financial Protection Bureau (CFPB).

This type of public disclosure data is important because it helps show whether lenders are serving the housing needs of their communities, gives public officials information that helps them make decisions and policies, and sheds light on lending patterns that could be discriminatory.

Mortgage approvals are intertwined with many other social concerns including employment, loan requirements, income, and all sorts of other. Data science provides tools for predicting whether a mortgage application will be accepted and understanding the factors that increase that decision. Digging into underlying patterns in HMDA data is the type of citizen science that can help provide greater visibility.

[Learn more...](https://www.datasciencecapstone.org/competitions/14/mortgage-approvals-from-government-data/)


## Problem Description

Predict the variable "accepted" (a binary variable) for each row of the test data set.

* Train a model using the inputs in train_values.csv and the labels train_labels.csv
* Predict value for each row in test_values.csv for which you don't know the true value of accepted.
* Output predictions in a format that matches submission_format.csv exactly.
* Upload predictions to this competition in order to get a score.

[Learn more...](https://www.datasciencecapstone.org/competitions/14/mortgage-approvals-from-government-data/page/44/)


## Tools used

* Python3 and Spyder IDE
* Numpy, Pandas and Scikit-learn
* Matplotlib and Seaborn
* Jupyter Notebooks
* Excel


## Folder contents

* Model
* Report
* Data


## Skills applied

* Managing a large dataset of 500,000 observations
* Using a cloud-based analytics environment (Kaggle Kernels)
* Hyperparameter tuning and feature engineering
* Statistical analysis


## Challenges

* Deploying a model that can rapidly train on a large dataset (LightGBM)
* Applying feature engineering to boost model accuracy (Loan to income ratio etc.)
* Calculating lender acceptance rate and applying that to new data (VLOOKUP)


## Result

The result of the final project was 84 / 100 due to a 72.1% accuracy against the test dataset. This placed the final model built with LightGBM and feature engineering in 44th position of the leaderboard out of 414 competitors (top 11%).

![Result](score.png)
![Top50](result.png)