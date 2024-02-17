# CAR PRICE PREDICTION MULTIPLE LINEAR REGRESSION

Implementing Multiple Linear Regression to predict Car Prices

## Table of Contents

- [Introduction](#introduction)
- [Data Source](#data-source)
- [Features](#features)
- [Learnings](#learnings)

## Introduction

The car company wants to enter a new market and needs an estimation of exactly which variables affect the car prices.
The goal is:
  - Which variables are significant in predicting the price of a car?
  - How well do those variables describe the price of a car?

## Data Source
This data set is taken from Kaggle, the link to which is: 
  - https://www.kaggle.com/datasets/hellbuoy/car-price-prediction

## Features

This is a very detailed and explanatory project for beginners who are looking to get their hands dirty with Exploratory Data Analysis, Hypothesis Testing, and Linear Regression.

- Exploratory Data Analysis of Categorical and Numerical Variables.
- Using 1 Sample t-test to check if a sample car feature (Average Horsepower in a Sedan) from my dataset is a good representation of the population.
- Using Ordinary Least Squares (OLS) and Normal Equation.
- Using Gradient Descent and Cost Function.

## Learnings

The first real project I worked on, taught me several things:
- Getting comfortable with working with a relatively large and noisy dataset.
- Using and showcasing several Python techniques and libraries:
  1. Numpy
  2. Pandas
  3. Scipy
  4. Matplotlib
  5. Seaborn
  6. Scikit Learn
- Using techniques like:
  1. Outlier Detection
  2. Identifying Input Features and Target Variables.
  3. Visualizing different graphs for different variables.
  4. Visualizing relationships amongst different variables.
- Hypothesis Testing:
  1. Deciding which test to conduct.
  2. Defining a significant alpha value.
  3. Comparing the alpha with the p-value and t-calculated with t-critical to draw conclusions about the statistical significance and infer information about the population based on the sample.
- Employing OLS and Normal Equation to build a Multiple Linear Regression Model
- Splitting the dataset into training and testing splits.
- Visualising the predictions and actual values via scatterplot.
- Using Regression Performance Metrics to check the accuracy of our model:
    1. Mean Absolute Error
    2. Mean Squared Error
    3. Root Mean Squared Error
    4. R2 Score
    5. Adjusted R2 Score
- Employing Gradient Descent to build the second Multiple Linear Regression Model.
- Feature Engineering:
  1. Introducing new features from the existing ones to prevent overfitting and save computational resources.
  2. Since introducing new features may increase the chances of introducing Multi-Collinearity in the dataset.
  3. Checking for Multi-Collinearity through Heatmap and Variance Inflation Factor (VIF).
  4. Choosing relevant features for the second model.
- Feature Scaling
  1. Using Z-Score Normalization to scale the input features for a better and more accurate model.
- Using Gradient Descent to build the second model.
- Visualising the predictions and actual values via scatterplot.
- Using Regression Performance Metrics to check the accuracy of our model:
  1. Mean Absolute Error
  2. Mean Squared Error
  3. Root Mean Squared Error
  4. R2 Score
  5. Adjusted R2 Score

Below you can find a few snippets of the project

![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/71816b84-6bba-4527-abfe-c08a980c02c3)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/4096e75e-2319-4aea-b93c-4dbdb156411b)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/ce9d06e0-22a3-4f46-8d04-80092b0bc256)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/817487e5-6a78-4e6f-bdd3-90418b913618)





