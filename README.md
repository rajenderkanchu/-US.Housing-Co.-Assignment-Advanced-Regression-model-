Project name:
**US.Housing Co.-Assignment (Advanced Regression model)**

Problem Statement:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
 
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
 
Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
Importing data
Data Understanding
Exploration & Cleaning
Exploratory Data Analysis(EDA)
correlation matrix and heatmap
Data Preparation
MinMax scaling on numerical features
Linear Regression
Building base model
Model 1: Building model using RFE
Model 2: Building model using 50 features
Final Model
Linear Regression Final Model Evaluation
Residual Analysis of Test
Linear Regression features and coefficients
Lasso Regression
Build final Lasso Regression model
Lasso Regression Model Evaluation
Ridge Regression
Build final Ridge Regression model
Ridge Regression Model Evaluation

## Conclusions

**Observations**

There are 33 significant features in the model
The features are sorted in the order of decreasing significance of the co-efficients (i.e. The most significant feature is at the top, followed by the next significant one and so on...)
The co-efficients are very close for Ridge and Lasso Regression models post regularization with slight variance to the model created by Linear Regression
However, the resultant selection of significant feature order still remains the same


The R2 Score, RSS and MSE are all very close for Linear Regression, Ridge and Lasso
Lasso has better scores by a very slight margin compared to Ridge and Linear Regression

## Contact
Rajender K
email Id: usreinvalid10@gmail.com

