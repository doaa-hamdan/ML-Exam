# Medical Insurance Cost Prediction using Machine Learning

## Overview

This project applies Machine Learning techniques to predict medical insurance charges using demographic and health-related data. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

## Dataset

The project uses the Insurance Dataset containing the following features:

* Age
* Sex
* BMI (Body Mass Index)
* Number of Children
* Smoker Status
* Region
* Medical Charges (Target Variable)

## Project Workflow

### 1. Data Exploration

* Dataset inspection
* Missing value check
* Duplicate detection and removal
* Statistical summary

### 2. Exploratory Data Analysis (EDA)

* Distribution of medical charges
* BMI vs Charges scatter plot
* Correlation matrix visualization
* Outlier detection using IQR

### 3. Data Preprocessing

* Standardization of numerical features
* One-Hot Encoding of categorical variables
* Train-Test Split

### 4. Machine Learning Models

#### Linear Regression

Baseline regression model used for prediction.

#### Ridge Regression

Regularized linear model with hyperparameter tuning using GridSearchCV.

#### Lasso Regression

Additional regularization model tested for comparison.

### 5. Model Evaluation

Models are evaluated using:

* RMSE (Root Mean Squared Error)
* R² Score
* 5-Fold Cross Validation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook


## Key Concepts Covered

* Data Cleaning
* Data Visualization
* Feature Scaling
* One-Hot Encoding
* Linear Regression
* Ridge Regression
* Lasso Regression
* Hyperparameter Optimization
* Cross Validation
* Model Evaluation

## Author

**Doaa Hamdan**

Machine Learning Exam Project
