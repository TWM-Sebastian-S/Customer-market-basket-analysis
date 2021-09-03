# Customer Market Basket Analysis

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Machine Learning Project in Python created to to perform market basket analysis with the application of Apriori and FP growth algorithms based on the concept of association rule learning.
Project included: 
  - Description of association rules and techniques with deep understanding of the algorithms.
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Perform Univariate & bi-variate analysis for both numeric and categorical variables
  - One hot encoding.
  - Prepare the data for modelling
  - Create models using Apriori and FPgrowth algorithms
  - Compare the performance of both models
  

## Problem Statement

Many business enterprises accumulate large quantities of data from their day-to-day operations. For example, huge amounts of customer purchase data are collected daily at the checkout counters of grocery stores. Such data is commonly known as market basket transactions.

Such valuable information can be used to support a variety of business-related applications such as marketing promotions, inventory management, and customer relationship management.

Association analysis, which is useful for discovering interesting relationships hidden in large data sets uncovers relationships that can be represented in the form of sets of items present in many transactions, which are known as frequent itemsets, or association rules. Retailers can use these types of rules to help them identify new opportunities for crossselling their products to the customers.

Food Mart (FM) is a chain of convenience stores in the United States. The private company's headquarters are located in Mentor, Ohio, and there are currently approximately **325 stores located in the US**. Food Mart operates on the franchise system.

In the following project I will work with the Telecom Company database containing information regarding their customers and churn situation.

## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / Scikitlearn

**ML Resources:** Logistic Regression / Gradient Boosting / Cross-validation / AUC / ROC / Confusion Matrix

## Model Building

First, I built a logistic regression as it's a statistical model that uses a logistic function to model a binary dependent variable (true/false, yes/no, 0/1, etc), although many more complex extensions exist. The model is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead or healthy/sick. Churn is exactly that case.

I also performed Gradient Boosting as a crosscheck using a hyperparameter tuning with a CV grid to find the best gradient boosting model. I crossvalidated using 5 folds.

## Model Performance

I tried two different models and evaluated them using ROC curve and Precission Recall Curve.

Generally, the use of ROC curves and precision-recall curves are as follows:

- ROC curves should be used when there are roughly equal numbers of observations for each class.
- Precision-Recall curves should be used when there is a moderate to large class imbalance.

![ROC Curve](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/ROC%20curve.JPG "ROC Curve") ![Precision Recall Curve](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/Precision%20Recall%20Curve.JPG "Precision Recall Curve")


## Recursive Feature Elimination

I analyzed all variables involved and eliminated those that were the weakest ones. 

## Conclusion

I came up with a gradient boosting model with only the strongest features and a solid performance against Logistic Regression. The key drivers are as follows:

![Key drivers of churn](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/Key%20drivers%20of%20churn.JPG "Key drivers of Churn")

[GitHub Repository](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression)
