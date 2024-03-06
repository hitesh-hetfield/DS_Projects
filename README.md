# Bank Term Deposit Prediction Project

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem)
- [Objective](#objective)
- [Data Source](#data-source)
- [Features](#features)
- [Learnings](#learnings)
- [Conclusion](#conclusion)
- [Project Snippets](#project-snippets)

## Introduction

- Term deposits are a significant source of income for banks, involving cash investments held at financial institutions.
- Banks employ various outreach strategies to enhance term deposit sales, including email marketing, advertisements, telephonic marketing, and digital marketing.

## Problem
- Telephonic marketing campaigns remain effective for customer outreach but require substantial investments in call centers. 
- Identifying potential customers likely to convert beforehand is crucial for targeted calling.

## Objective
- The objective of this project is to predict whether a client will subscribe to a term deposit.

## Data Source
This data set is taken from Kaggle, the link to which is: 
  - [https://www.kaggle.com/datasets/hellbuoy/car-price-prediction](https://www.kaggle.com/datasets/thedevastator/bank-term-deposit-predictions)(https://huggingface.co/datasets/Andyrasika/banking-marketing)

## Features

This is my first Machine Learning Project in which I've trained 3 Classification Models:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4.  To get the data to the point of training the Machine Learning Model, I employed techniques like:
    - Checking null and duplicate values.
    - Using Exploratory Data Analysis on Categorical and Numerical Variables:
        - Visualizing and Exploring the distribution of Categorical Variables through a Countplot.
        - Visualizing and Exploring the distribution of Numerical Variables through a Histplot and Violinplot.
        - Visualizing and Exploring outliers through Boxplot.
        - Visualizing and Exploring the relationship between the Target Variable and Numerical Variables via Lineplot, and Stacked Histplot.
        - Visualizing and Exploring the relationship between the Target Variable and Categorical Variables via Countplot by giving the hue of the Target Variable.
        - Visualizing and Exploring the correlation between the Target Variable and Numerical Variables via Heatmap.
5. Splitting the Data into Training and Testing Sets.
6. Encoding the Categorical Variables using OneHotEncoding.
7. Scaling down the Numerical Variables using StandardScaler and MinMaxScaler.
8. Using SMOTE to tackle Class Imbalance.
9. Building the 3 Classification Models.
10. Measuring their performance metrics which include:
    - Precision
    - Recall
    - F1 Score
    - Accuracy
    - AUC Percentage
    - ROC Curve
11. Employing Feature Engineering to improve Model Performance.
12. Using pandas function to group extreme numerical variables and classify them into categories using:
    - defining custom functions
    - .apply()
    - .map()
    - .cut()
    - .replace()
    - 
## Learnings

- This project was a vast ocean of learning, immersing me in a sea of knowledge and growth.
1. Interpreting results between Categorical and Numerical Variables
3. Learning practical use-case of Deep Copy.
4. Tuning Sklearn models as per my requirements:
    1. Under OneHotEncoder setting parameters like:
        - drop, sparse_output, handle_unknown
    2. Using Standard Scaling to scale down the Numerical Columns.
    3. Using set_output to transform the encoded columns directly into a pandas dataframe.
5. Integrating fundamental Python datatypes into my workflow by storing the metrics in a dictionary and using said dictionary to plot and compare the metrics of different models.
6. Clubbing extreme Numerical Variables into categories by:
    - grouping them under different brackets.
    - defining custom functions for these brackets.
    - mapping the values in the Numerical Columns into defined brackets.
7. Merging similar Categorical Variables into one to reduce the # of categories and hence reduce the dimensions.
8. Making new columns based on the percentage of the target variable, converting them into categories.
9. Scaling down the remaining Numerical Variables using MinMaxScaler
10. Checking Class Imbalance:
    - Using SMOTE to oversample the minority class in the target variable.

## Conclusion

This project provided valuable insights into predicting term deposit subscriptions using machine learning techniques. By leveraging exploratory data analysis, preprocessing, model building, and evaluation, the project aimed to optimize telephonic marketing campaigns for enhanced customer conversion rates. Further refinements and explorations could include advanced modeling techniques and the incorporation of additional features for more accurate predictions.

## Project Snippets

Below you can find a few snippets of the project

![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/71816b84-6bba-4527-abfe-c08a980c02c3)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/4096e75e-2319-4aea-b93c-4dbdb156411b)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/ce9d06e0-22a3-4f46-8d04-80092b0bc256)
![image](https://github.com/hitesh-hetfield/DS_Projects/assets/151897902/817487e5-6a78-4e6f-bdd3-90418b913618)





