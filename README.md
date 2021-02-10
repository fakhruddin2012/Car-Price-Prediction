
# Car-Price-Prediction
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)



## Problem Statement:
-Here I have the dataset contains information about used cars listed on www.cardekho.com. I am using Random Forest Regression model to predict the selling price of Cars.

![image](https://user-images.githubusercontent.com/55452866/107490653-2d199700-6bb0-11eb-9249-808619568455.png)

## Approach:
## Data Preprocessing:
-The dataset have 301 records and around 9 features.
-The dataset does not have any null values.
-I have calculated the age of the car by subtracting the current year with the feature Year which is the year in which car hit the road.
-Than I dropped the year columns as I have calculated the age of the car.
-The dataset have some categorical columns to which I converted into numerical values with the help of pandas's get_dummies.
-To understand the data much more I calculated the correlation between the features.
-I used ExtraTreesRegressor to calculate which features plays important role.


