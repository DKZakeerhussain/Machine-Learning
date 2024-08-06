# Car Price Prediction using Linear Regression

This project demonstrates how to perform a regression analysis to predict car prices. The steps include data cleaning, data transformation using log transformation, model fitting, and making predictions using the Linear Regression model from scikit-learn.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Steps](#steps)
  - [Data Cleaning](#data-cleaning)
  - [Data Transformation](#data-transformation)
  - [Model Fitting](#model-fitting)
  - [Making Predictions](#making-predictions)
- [Results](#results)


## Introduction

The aim of this project is to predict car prices using a linear regression model. This involves several steps such as data cleaning, transforming the data using log transformation, fitting a linear regression model, and making predictions.

## Dataset

The dataset used for this project contains various features of cars, including their prices, model, mileage and brands. The dataset should be in a CSV file named `car_prices_dataset.csv`.

## Requirements

- Python 3.6 or above
- pandas
- numpy
- scikit-learn
- matplotlib

## Data Cleaning
- Load the dataset using pandas.
- Handle missing values by removing rows with missing target values or filling missing feature values.
- Remove any duplicate rows.


## Data Transformation

- Apply log transformation to the target variable to normalize its distribution.

## Model Fitting

- Split the dataset into training and testing sets.
- Fit a Linear Regression model to the training data.

## Making Predictions
- Make predictions on the test data.
- Transform the predictions back to the original scale by applying the exponential function.

## Results
Evaluate the model performance using metrics such as Mean Squared Error (MSE) and R^2 Score.
