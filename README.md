Overview

This project focuses on predicting flight delays using polynomial regression models. The objective is to analyze flight data, fit polynomial regression models of various degrees, and evaluate their performance through cross-validation to identify the optimal model.

Project Structure
Data: The project utilizes a dataset containing information related to scheduled flight departures and delays. The data should include features like scheduled departure times and actual delay metrics.
Analysis Script: Contains the logic for data processing, polynomial regression fitting, and model evaluation.
Model Evaluation: Cross-validation is employed to assess model accuracy and report mean squared error (MSE) for different polynomial degrees.
Key Components
Polynomial Regression
Polynomial regression is used to capture non-linear relationships in the data. The project tests polynomial degrees from 1 to 7 to find the best-fit model for predicting flight delays.

Cross-Validation
Purpose: To ensure that the model generalizes well to unseen data by splitting the dataset into training and validation sets.
Method: 10-fold cross-validation is used, where the dataset is divided into 10 parts, and the model is trained and validated across these parts.
Output: The mean squared error (MSE) for each polynomial degree is calculated and recorded to identify the most accurate model.
