# Predicting Churn Using Gradient Boosting and Logistic Regression

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Machine Learning Project in Python created to find out the key drivers that lead to churn and predict the customer churn.
Project included: 
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Perform Univariate & bi-variate analysis for both numeric and categorical variables
  - Feature engineering and feature selection
  - Prepare the data for modelling
  - Create models using multiple algorithms:
    - Logistic Regression
    - GradientBoosting
  - Perform Hyper-parameter tuning
  - Compare the performance of different models using multiple metrics
  - Recursive feature elimination


## Problem Statement

A Telecom Company has evidence of customer churn and has provided a dataset with certain information regarding their clients. Customer attrition, also known as customer churn, customer turnover, or customer defection, is the loss of clients or customers.

Why is it bad? Because revenue that was once captured by the business is no longer going to repeat. So, eventually, churn leads to increase company's efforts to acquire new clients, evetually increasing CAC (customer acquisition cost) & reducing profits. Moreover, acquiring new customers is more expensive than maintaining existing ones. The more customers you churn, the more money you must spend to regain new one that will cover the loss of business.

A good practice that most of the companies implement, is related to target potential churn customers in advance to try to see if there is space to take action beforehand. Therefore, any good CRM must have a solid prediction model to target potential loss of customers in advance.

In the following project I will work with the Telecom Company database containing information regarding their customers and churn situation.

## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / Scikitlearn

**ML Resources:** Logistic Regression / Gradient Boosting / Cross-validation / AUC / ROC / Confusion Matrix

## Model Building

First, I built a logistic regression as it's a statistical model that uses a logistic function to model a binary dependent variable (true/false, yes/no, 0/1, etc), although many more complex extensions exist. The model is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead or healthy/sick. Churn is exactly that case.

I also performed Gradient Boosting as a crosscheck using a hyperparameter tuning with a CV grid to find the best gradient boosting model. I crossvalidated using 5 folds.

## Model Performance

I tried three different models and evaluated them using Mean Absolute Error. I chose MAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.


## Conclusion


[GitHub Repository](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression)
