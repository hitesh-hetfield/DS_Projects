# TERM DEPOSIT PREDICTION USING LOGISTIC REGRESSION, DECISION TREE and RANDOM FOREST
Implementing Multiple Linear Regression to predict Car Prices

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem)
- [Objective](#objective)
- [Data Source](#data-source)
- [Features](#features)
- [Learnings](#learnings)

## Introduction

- Term Deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. 
- The bank has various outreach plans to sell term deposits to their customers such as:
    - Email Marketing
    - Advertisements
    - Telephonic Marketing
    - Your money is invested for an agreed rate of interest over a fixed amount of time, or term. 
    - Digital Marketing

## Problem
- Telephonic marketing campaigns still remain one of the most effective way to reach out to 
people. 
- Telephonic marketing require huge investment as large call centers are hired to actually 
execute these campaigns. 
- Hence, it is crucial to identify the customers most likely to convert beforehand so that they 
can be specifically targeted via call.

## Objective
- The goal is to predict if the client will subscribe to a term deposit (variable y)

## Data Source
This data set is taken from Kaggle, the link to which is: 
  - [https://www.kaggle.com/datasets/hellbuoy/car-price-prediction](https://www.kaggle.com/datasets/thedevastator/bank-term-deposit-predictions)

## Features

This is my first Machine Learning Project in which I've trained 3 Classification Models:
1. Logistic Regression
2. Decision Tree
3. Random Forest
To get the data to the point of training the Machine Learning Model, I employed techniques like:
  - Checking null and duplicate values.
  - Using Exploratory Data Analysis on Categorical and Numerical Variables:
    - Visualizing and Exploring the distribution of Categorical Variables through a Countplot.
    - Visualizing and Exploring the distribution of Numerical Variables through a Histplot and Violinplot.
    - Visualizing and Exploring outliers through Boxplot.
    - Visualizing and Exploring the relationship between the Target Variable and Numerical Variables via Lineplot, and Stacked Histplot.
    - Visualizing and Exploring the relationship between the Target Variable and Categorical Variables via Countplot by giving the hue of the Target Variable.
    - Visualizing and Exploring the correlation between the Target Variable and Numerical Variables via Heatmap.
- Splitting the Data into Training and Testing Sets.
- Encoding the Categorical Variables using OneHotEncoding.
- Scaling down the Numerical Variables using StandardScaler and MinMaxScaler.
- Building the 3 Classification Models.
- Measuring their performance metrics which include:
  - Precision
  - Recall
  - F1 Score
  - Accuracy
  - AUC Percentage
  - ROC Curve
- 

  
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





