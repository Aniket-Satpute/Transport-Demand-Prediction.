# Transport-Demand-Prediction.
![start slide](https://th.bing.com/th/id/OIP.2CKdbPuS-M2cQ8sn_TOL1wHaFX?pid=ImgDet&rs=1)

## Problem Statement :
This challenge asks you to build a model that predicts the number of seats that Mobiticket can expect to sell for each ride, i.e. for a specific route on a specific date and time. There are 14 routes in this dataset.


## Objective :

The aim of the competition is to create a predictive model using traffic data provided from Uber
Movement and historic bus ticket sales data from Mobiticket to predict the number of tickets that will
be sold for buses into Nairobi from cities in "up country" Kenya.

## Introduction :

Nairobi is one of the most heavily congested cities in Africa. Each day thousands of Kenyans make
the trip into Nairobi from towns such as Kisii, Keroka, and beyond for work, business, or to visit
friends and family. The journey can be long, and the final approach into the city can impact the
length of the trip significantly depending on traffic. How do traffic patterns influence people’s
decisions to come into the city by bus and which bus to take? Does knowing the traffic patterns in
Nairobi help anticipate the demand for particular routes at particular times.

## Data prepping :

In this project, we are analyzing the various aspects with different use cases which covers many
aspects of airbnb listings. It helps in not only understanding the meaningful relationships between
attributes but it also allows us to do our own research and come-up with our findings.

The data set contains 51,645 observations and 10 columns

To understand data integrated details, we find out done null values and unique values from which
and we came to know there no null values

## Approach :

We performed the Outliers treatment and normalized the features for better results. I have used supervised learning regression analysis models like linear regression, implementing lasso regression and ridge regression, training gradient boosting regressor, training XG boost, random forest for the purpose of training the dataset to predict future supply 
Hyperparameter tuning plays an important role to predict the best model among the above regression models

## Conclusion :

This resulting model can be used by Mobiticket and bus operators to anticipate customer demand for certain rides, to manage resources and vehicles more efficiently, to offer promotions and sell other services more effectively, such as micro-insurance, or even improve customer service by being able to send alerts and other useful information to customers. We used different type of regression algorithms to train our model like, out of them XG Boost with tuned hyperparameters gave the best result.
