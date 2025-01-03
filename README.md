# Housing Data Analysis and Linear Regression

This repository contains a Python script that performs data analysis and linear regression on a housing dataset. The goal is to predict the `median_house_value` based on the `median_income` feature. The code uses libraries such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn` for data manipulation, visualization, and machine learning.

## Overview

The script performs the following tasks:
1. Loads a housing dataset from a CSV file.
2. Visualizes the relationship between `median_income` and `median_house_value` using a scatter plot.
3. Splits the dataset into training and testing sets.
4. Trains a linear regression model to predict `median_house_value` based on `median_income`.
5. Evaluates the model using Root Mean Squared Error (RMSE).
6. Visualizes the regression line on top of the scatter plot.
7. Prints the regression equation and interprets the slope.


## Dataset

The dataset used in this project is stored in a CSV file named `housing.csv`. It contains the following columns:
- `longitude`
- `latitude`
- `housing_median_age`
- `total_rooms`
- `total_bedrooms`
- `population`
- `households`
- `median_income`
- `median_house_value`
- `ocean_proximity`

The script focuses on the relationship between `median_income` (independent variable) and `median_house_value` (dependent variable).

## Code Explanation

1. **Loading the Dataset :**
The dataset is loaded from housing.csv using pandas. Only specific columns are selected for analysis.

2. **Preparing the Data :**
median_income is used as the independent variable (x).

median_house_value is used as the dependent variable (y).

3. **Visualizing the Data :**
A scatter plot is created to visualize the relationship between median_income and median_house_value.

4. **Splitting the Data :**
The dataset is split into training (80%) and testing (20%) sets using train_test_split.

5. **Training the Model :**
A linear regression model is trained using the training data.

6. **Making Predictions :**
The model predicts median_house_value for the test data.

7. **Evaluating the Model :**
The model's performance is evaluated using RMSE.

8. **Visualizing the Regression Line :**
The regression line is plotted on top of the scatter plot.

9. **Printing the Regression Equation :**
The equation of the regression line is printed, along with an interpretation of the slope.
