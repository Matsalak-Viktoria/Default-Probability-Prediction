# Default Probability Prediction | [View Code](https://github.com/Matsalak-Viktoria/Default-Probability-Prediction/blob/main/Default_Probability_Prediction.ipynb)

## Overview
This project explores the implementation and evaluation of a machine learning pipeline for loan default prediction using customer credit and loan data.

The main goal of the project is to build a classification model for predicting the probability of loan default using exploratory data analysis, data preprocessing, feature engineering, feature selection, and hyperparameter tuning with Optuna.

The project focuses on the following prediction task:
- Loan Default Prediction - Predicting the probability that a customer will default on a loan based on demographic, financial, and credit history information.

## Objectives

## Dataset

## Workflow

## Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Methods
### Data Preprocessing
**For Outlier Detection**:
- Missing value imputation (Median)
- Feature scaling (StandardScaler)

**For Model Training**:

**Numerical features**:
- Missing value imputation (Median)
- Feature scaling (StandardScaler)

**Categorical features**:
- Missing value imputation (Most Frequent)
- One-Hot Encoding

### Outlier Detection
- Isolation Forest

### Machine Learning Models
- Logistic Regression
- Gaussian Naive Bayes
- Decision Tree
- K-Nearest Neighbors (KNN)

**Hyperparameters optimized**:
- Logistic Regression: Regularization strength (C)
- Decision Tree: Maximum tree depth (max_depth)
- K-Nearest Neighbors (KNN): Number of neighbors (n_neighbors)

### Validation Strategy
**Train/Test Split + GridSearchCV**:
- Train/Test split for final model evaluation
- GridSearchCV with 5-Fold Cross-Validation for hyperparameter optimization

### Evaluation Metrics

## Results
