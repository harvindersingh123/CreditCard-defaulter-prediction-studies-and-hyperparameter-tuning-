# CreditCard-defaulter-prediction-studies-and-hyperparameter-tuning
Credit Card Defaulter Prediction

## Overview

This project focuses on predicting whether a credit card client will default on their payment in the next month using machine learning classification models. The dataset used is publicly available from the UCI Machine Learning Repository and contains information about credit card clients in Taiwan.

## Dataset

The dataset is sourced from the UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients). It contains information on:

## Demographic attributes (e.g., age, gender, education)

Payment history

Credit limits

Default status (target variable)

The target variable indicates whether the client defaulted on their payment in the subsequent month.

## Objectives

### Data Exploration and Visualization:

Analyze the dataset to understand its structure and characteristics.

Use visualizations such as histograms and pair plots to uncover trends and patterns.

### Data Preprocessing:

Handle missing or erroneous values.

Scale numeric features and encode categorical variables.

Develop a robust data preprocessing pipeline.

### Model Development and Hyperparameter Tuning:

Train two classifiers:

Random Forest

K-Nearest Neighbors (KNN)

Perform hyperparameter tuning using Grid Search to identify the best parameters for each model.

Evaluate model performance using cross-validation and compare results.

## Methodology

### Exploratory Data Analysis (EDA):

Investigate the distributions of features and relationships between them.

Identify and handle outliers and skewed data.

### Model Training:

Implement classification models.

Optimize the models with hyperparameter tuning to achieve the best performance.

### Model Evaluation:

Use metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to compare model performance.

Analyze cross-validation results to determine the most effective model.

## Tools and Libraries

Python

Pandas and NumPy for data manipulation

Matplotlib and Seaborn for visualization

Scikit-learn for model development and evaluation
