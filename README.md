# # Spaceship Titanic Data Analysis

## Overview
This project involves the analysis of data from the Titanic Spaceship dataset, focusing on data preprocessing, visualization, and the application of various classification methods. The goal is to predict passengers' transportation status using machine learning techniques.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Methods and Explanations](#methods-and-explanations)
- [Results](#results)

## Prerequisites
Ensure that you have the necessary R packages installed:

- `tidyverse`
- `glmnet`
- `ROCR`
- `caret`
- `class`
- `e1071`
- `ranger`

## Methods and Explanations

- **Lasso Regression**:
Lasso regression is implemented using the glmnet package. The model is optimized with cross-validation using the AUC as the evaluation metric. This method helps identify essential features that contribute to the classification task.

- **K-Means**:
K-Means is an unsupervised learning algorithm that partitions the data into K distinct, non-overlapping clusters based on feature similarity.
  
- **Hierarchical Clustering**:
Hierarchical Clustering is an unsupervised learning technique that builds a hierarchy of clusters by either successively merging or splitting existing groups.
  
- **Spectral Clustering**:
Spectral Clustering uses eigenvalues of a similarity matrix to reduce dimensionality before clustering in fewer dimensions.
  
- **AdaBoost**:
AdaBoost, or Adaptive Boosting, is an ensemble learning method that combines multiple weak classifiers to form a strong classifier by iteratively adjusting the weights of data points.

## Results 
The project evaluates and reports the performance of each classification method, including accuracy, AUC, and confusion matrices.




