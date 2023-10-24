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
1. Data Preprocessing
The code cleans the data by dropping missing values and splitting columns to create new features. It also converts binary values to meaningful categories (VIP, CryoSleep, Transported).

2. Data Visualization
The project generates histograms and visualizations to explore data distributions and assess skewness.

3. Lasso Regression
Lasso regression is implemented using the glmnet package. The model is optimized with cross-validation using the AUC as the evaluation metric. This method helps identify essential features that contribute to the classification task.

4. K-Nearest Neighbors (KNN)
KNN classification is performed using the caret package, with a tuning process to find the optimal k value. KNN classifies data points based on the majority class of their k-nearest neighbors.

5. Support Vector Machine (SVM)
SVM classification with a linear kernel is executed using the e1071 package. SVM is a powerful method for separating data points into different classes using a hyperplane.

6. Random Forest
A random forest classifier is built using the ranger package. Hyperparameter tuning is conducted to enhance model performance. Random Forest combines the predictions of multiple decision trees.

## Results 
The project evaluates and reports the performance of each classification method, including accuracy, AUC, and confusion matrices.




