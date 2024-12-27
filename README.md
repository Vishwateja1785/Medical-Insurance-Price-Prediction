# Medical Insurance Price Prediction

## Project Overview

This project focuses on analyzing factors that influence medical insurance premium prices and comparing various ensemble machine learning models to predict insurance prices accurately. The analysis includes Exploratory Data Analysis (EDA) and the implementation of three regression-based ensemble ML models: Extreme Gradient Boosting (XGBoost), Gradient Boosting Machine (GBM), and Random Forest (RF).

## Dataset

The dataset used in this project contains the following features:

- Age
- Diabetes
- Blood Pressure Problems
- Any Transplants
- Any Chronic Diseases
- Height
- Weight
- Known Allergies
- History of Cancer in Family
- Number of Major Surgeries
- Premium Price (Target Variable)

## Exploratory Data Analysis (EDA)

The EDA phase included:

- Descriptive statistics of numerical and categorical variables
- Visualization of feature distributions
- Correlation analysis between features
- Chi-square tests for categorical variable relationships
- Feature scaling and normalization

## Feature Engineering

- BMI calculation and categorization
- One-hot encoding for categorical variables

## Model Implementation

Three ensemble machine learning models were implemented and compared:

1. Extreme Gradient Boosting (XGBoost)
2. Gradient Boosting Machine (GBM)
3. Random Forest (RF)

## Model Evaluation

The models were evaluated using the following metrics:

- R-squared (R2) score
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Cross-validation score

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
