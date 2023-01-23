# Consumer_Lifetime_Value_Prediction

## Problem Statement
VahanBima is one of the leading insurance companies in India. It provides motor vehicle insurances at best prices with 24/7 claim settlement. It offers different types of policies for both personal and commercial vehicles. It has established its brand across different regions in India.

Around 90% of the businesses today use personalized services. The company wants to launch different personalized experience programs for customers of VahanBima. The personalized experience can be dedicated resources for claim settlement, different kinds of services at doorstep, etc. Inorder to do so, they would like to segment the customers into different tiers based on their customer lifetime value (CLTV).

Inorder to do it, they would like to predict the customer lifetime value based on the activity and interaction of the customer with the platform. So, as a part of this challenge, your task at hand is to build a high performance and interpretable machine learning model to predict the CLTV based on the user and policy data.

## About Data
We are provided with the sample dataset of the company holding the information of customers and policy such as highest qualification of the user, total income earned by a customer in a year, employee status,  policy opted by the user, type of policy and so on and the target variable indicating the total customer lifetime value. The train data consists of 89392 rows and 12 columns, and the test data consists of 59595 rows and 11 columns. The target variable is a continuous variable hence, making the problem a Regression Problem.

## Project Overview
* The objective of the problem is to accurately predict the Customer Lifetime Value(CLV) of the customer for an Auto Insurance Company
* Performed EDA to understand the relation of target variable CLV with the other features.
* Performed necessary data preprocessing steps like One Hot Encoding, Scaling/Normalization etc.
* Supervised Regression Models like Linear Regression, Ridge Regression, DecisionTree Regression, Random Forest Regression, Adaboost Regression, XGBoost Regression, Gradient Boost Regression, CatBoost Regression and Bagging Regressor.
* After doing the hyperparameter tuning, CatBoost Regression gave the best MSE and R^2 score values.

## Evaluation Metric
Mean Squared Error (MSE) and R^2 score were chosen as the metric for the model.

## Models
<img width="221" alt="image" src="https://user-images.githubusercontent.com/108981162/213963239-fab81c0d-c9cb-4b6b-b1c8-37383f0defcd.png">

## Final Model
By comparing MSE and R^2 score results of models and then we choose the best model as the CatBoost Regressor, having the best evaluation scores.


