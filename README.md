# Customer Market Basket Analysis

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Machine Learning Project in Python created to perform market basket analysis with the application of Apriori and FP growth algorithms based on the concept of association rule learning.
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

In the following project I will work with the transactions dataset containing information regarding customers and purchases.

## Code and resources used
**Python Version:** 3.9

**Packages:** Pandas / Numpy / Seaborn / mlextend

**ML Resources:** Association Rules

## Model Building

I created two different models doing some feature engineering and one hot encoding. I also used and defined the parameters of support, lift and confidence in relation to association rules.

## Model Performance

Apriori was significantly more computationally expensive with smal thresholds, but as the threshold increase, it lower it's performing time. On the other hand, FPgrowth was faster at the beginning was the decrease rate when decreasing the threshold, was smaller than Apriori.

![Models Performance](https://github.com/TWM-Sebastian-S/Customer-market-basket-analysis/blob/main/Models%20performance.JPG "Models Performance")



[GitHub Repository](https://github.com/TWM-Sebastian-S/Customer-market-basket-analysis)
