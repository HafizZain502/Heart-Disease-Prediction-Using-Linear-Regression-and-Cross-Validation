# Heart-Disease-Prediction-Using-Linear-Regression-and-Cross-Validation
This repository contains a machine learning project focused on predicting heart disease using linear regression and cross-validation techniques. The project utilizes a dataset that includes clinical parameters which may be indicative of heart conditions.

## Project Overview
The goal of this project is to apply linear regression to predict heart disease and evaluate the model's performance using various metrics. We also employ cross-validation to ensure that our model's performance is robust and generalizes well to unseen data.

## Dataset
The dataset, Heart.csv, comprises several clinical features such as Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol levels, Fasting Blood Sugar, Resting ECG results, Maximum Heart Rate achieved, Exercise Angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, and a binary target variable indicating the presence of heart disease.

## Methodology
The code follows a structured machine learning pipeline:

## Handling Missing Values: 
We begin by checking for and imputing missing values to maintain data integrity.

## Data Splitting: 
The dataset is split into training and testing sets, with a 70-30 split to balance between learning and validation capacity.

## Linear Regression: 
We implement a linear regression model using the training data and predict the outcome on the testing set.

## Evaluation Metrics: 
The model's performance is evaluated on the training data using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Cross-Validation: 
To validate the model's stability, we perform cross-validation with different values of K and reassess the performance metrics.

## Interpretation:
We interpret the changes in error metrics post cross-validation to understand the model's predictive power and generalization.
Results and Interpretation

The project concludes with an interpretation of the error metrics before and after cross-validation. The initial evaluation shows promising results; however, cross-validation provides a more realistic assessment of the model's performance on unseen data. The slight increase in error metrics with cross-validation suggests that while the model fits the training data well, it is crucial to consider its ability to generalize when evaluating its performance.

## Conclusion
This project serves as a comprehensive approach to predicting heart disease using machine learning. It demonstrates the importance of cross-validation in assessing a model's effectiveness and provides a framework for future work on similar datasets.

