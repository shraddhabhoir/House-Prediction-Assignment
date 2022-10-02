# House Prediction Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Background of the project
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.
- Business Goal
The business goal is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used?

https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv

## Conclusions
- With Lasso model, R2 score on training set is 91.9% and R2 score on testing set is 85.6% which is good. Model has performed well on train and test data.
- With Ridge model, R2 score on training set is 92.0% and R2 score on testing set is 87.8% which is good. Model has performed well on train and test data.
- Model evaluation results for both lasso and ridge model on train data as well as test data are at par. Ridge model is performing slightly better.
- We have evaluated models based on 257 features. Since most of the features are eliminated by Lasso hence we will select Lasso as the best model.
- Final model slected is Lasso Regression with alpha 0.00025. 
- Top 5 significant features in predicting the price of a house are GrLivArea, PoolQC_Gd, OverallQual, OverallCond, Condition2_PosN.
- This model now can be used further for predictions of the house prices.

## Technologies Used
- Numpy
- Pandas
- Matplotlib.pyplot
- seaborn
- sklearn

## Acknowledgements

- This project was inspired by Advanced Regression Assignment from Upgrad AIML course.

## Contact
Created by [@shraddhabhoir] - feel free to contact me!
https://github.com/shraddhabhoir
