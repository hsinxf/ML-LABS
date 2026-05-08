# SVM Iris Classification Project

## Overview

This project demonstrates how to use a Support Vector Machine (SVM) model to classify iris flowers using the Iris dataset. The notebook includes data exploration, visualization, model training, evaluation, and hyperparameter tuning using GridSearchCV.

## Dataset

The project uses the Iris dataset available in the seaborn library. The dataset contains 150 samples of iris flowers from three species:

- Setosa
- Versicolor
- Virginica

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Steps

### 1. Import Libraries

Required libraries for data analysis, visualization, and machine learning are imported.

### 2. Load the Dataset

The Iris dataset is loaded using seaborn and displayed for inspection.

### 3. Exploratory Data Analysis

The notebook includes:

- Pairplot visualizations
- KDE plots
- Feature comparison between species

### 4. Data Preparation

The dataset is divided into:

- Features (X)
- Target labels (y)

The data is then split into training and testing sets.

### 5. Train the SVM Model

An SVM classifier is created and trained using the training data.

### 6. Model Prediction

Predictions are generated using the test dataset.

### 7. Model Evaluation

The model performance is evaluated using:

- Confusion Matrix
- Classification Report

### 8. Hyperparameter Tuning

GridSearchCV is used to find the best parameters for the SVM model.

Parameters tested:

- C
- gamma
- kernel

## Results

The model achieved high classification accuracy on the Iris dataset. Hyperparameter tuning improved the model performance and reduced classification errors.

## How to Run

1. Install the required libraries:

```bash
pip install pandas seaborn matplotlib scikit-learn notebook
```
