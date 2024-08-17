# Student Performance Classification

## Project Overview

This project aims to classify student performance into four categories: Poor, Average, Good, and Excellent. It involves applying and comparing several classification algorithms to determine which method provides the most accurate predictions.

## Classification Methods

The following classification algorithms are utilized:

- **Logistic Regression:** Models the probability of each performance category based on input features.
- **Linear Discriminant Analysis (LDA):** Finds linear combinations of features that best separate the classes.
- **Quadratic Discriminant Analysis (QDA):** Handles non-linear class boundaries by modeling each class with its own covariance matrix.
- **K-Nearest Neighbors (KNN):** Classifies instances based on the majority class of their nearest neighbors.
- **Support Vector Machine (SVM):** Finds the optimal hyperplane for class separation, with kernel functions to handle non-linearity.
- **Decision Trees:** Creates a tree-like model of decisions based on feature values, offering a clear and interpretable classification approach.

## Evaluation Metrics

Each algorithm’s performance is evaluated using the following metrics:
- **Accuracy:** The proportion of correctly classified instances.
- **Precision:** The proportion of true positive predictions among all positive predictions.
- **Recall:** The proportion of true positive predictions among all actual positives.
- **F1-Score:** The harmonic mean of precision and recall, providing a single metric for model performance.

## Objective

The goal of this project is to identify the most effective classification method for predicting student performance and to provide insights into the factors influencing performance levels.
