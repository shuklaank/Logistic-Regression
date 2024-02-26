# Logistic-Regression

## Introduction
This README provides information on a custom implementation of the Logistic Regression class, which includes a new function called remove_index. The purpose of this function is to remove a specific record from the training set, and it is designed to be seamlessly integrated into the existing LogisticRegression class.

## LogisticRegression Class
Class Overview
The LogisticRegression class is designed to perform logistic regression for binary classification tasks. It includes methods for training the model, making predictions, and evaluating performance.

## New Function: remove_index
The remove_index function is a valuable addition to the LogisticRegression class. It takes an index as input and removes the associated record from the training set. This function ensures that the model is capable of training on data with a specific data point removed.

## Integration with run_model Function
To ensure that the model trains on the updated dataset after removing a data point, the remove_index function should be called inside the run_model function at an appropriate location.

## Impact of Removing Data Points 1 and 39
Removing data points 1 and 39 has a significant effect on the predicted probability of the model. The impact is attributed to the specific characteristics of these data points, which may hold substantial influence on the decision boundary learned by the model during training. The removal of these data points alters the underlying patterns the model has learned, leading to changes in predictions.

## Plotting the Decision Boundary
To visually understand the impact of removing data points 1 and 39, it is recommended to plot the decision boundary both before and after removal. This visual representation will help in understanding how the decision boundary changes after the removal of specific data points.
