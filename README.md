
# Car-Price-Prediction
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
* [Model Implementation](#Model-Implementation)
* [Saving the Model](#Saving-the-Model)
* [Deploying the model](#Deploying-the-model)



## Problem Statement:
-Here I have the dataset contains information about used cars listed on www.cardekho.com. I am using Random Forest Regression model to predict the selling price of Cars.

![image](https://user-images.githubusercontent.com/55452866/107490653-2d199700-6bb0-11eb-9249-808619568455.png)

## Approach:
## Data Preprocessing:
(1)The dataset have 301 records and around 9 features.

(2)The dataset does not have any null values.

(3)I have calculated the age of the car by subtracting the current year with the feature Year which is the year in which car hit the road.

(4)Than I dropped the year columns as I have calculated the age of the car.

(5)The dataset have some categorical columns to which I converted into numerical values with the help of pandas's get_dummies.

(6)To understand the data much more I calculated the correlation between the features.

![image](https://user-images.githubusercontent.com/55452866/107491763-9b128e00-6bb1-11eb-8bdb-af10e93775f8.png)


(7)I used ExtraTreesRegressor to calculate which features plays important role.

![image](https://user-images.githubusercontent.com/55452866/107492171-1f651100-6bb2-11eb-91a0-c2396b311e4e.png)

## Model Implementation:
I used Random Forest model to fit the dataset.Below are the metrics which i got.

MAE: 0.9074563501808273

MSE: 5.211188443191459

RMSE: 2.282802760466059

The R2 score which I got was 0.7849.



