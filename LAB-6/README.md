# Ecommerce Customers Analysis

## Overview

This project analyzes the Ecommerce Customers dataset using Python and machine learning techniques. The objective is to explore customer behavior and build a predictive model to estimate the yearly amount spent by customers.

## Dataset

The dataset contains information about customers, including:

* Average Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent (target variable)

Some additional columns such as Email, Address, and Avatar are included but are not relevant for modeling.

## Steps Performed

### 1. Data Loading

The dataset was loaded into a Pandas DataFrame using the `read_csv` function.

### 2. Data Exploration

Initial exploration included:

* Viewing the first few rows using `head()`
* Inspecting data types and structure using `info()`
* Generating statistical summaries using `describe()`

### 3. Data Cleaning

* Checked for missing values
* Removed any null values if present
* Dropped irrelevant columns (Email, Address, Avatar)

### 4. Feature Engineering

* Selected only numerical features relevant to the prediction task
* Defined the target variable as "Yearly Amount Spent"

### 5. Data Preparation

* Split the dataset into training and testing sets using an 80/20 ratio
* Prepared feature matrix (X) and target vector (y)

### 6. Model Training

A Linear Regression model was used to learn the relationship between customer features and yearly spending.

### 7. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

A scatter plot of actual vs predicted values was also generated to visually assess performance.

## Results

The Linear Regression model was able to predict customer spending with reasonable accuracy. The evaluation metrics indicate that the model performs well on unseen data.

## Conclusion

This project demonstrates a complete machine learning workflow, including data preprocessing, model training, and evaluation. The results suggest that customer behavior metrics can be effectively used to predict spending.




