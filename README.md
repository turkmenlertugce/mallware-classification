# Machine Learning–Based Virus Classification

This repository presents a machine learning study focused on **rapid classification of computer virus types** using structured feature data. The project evaluates multiple classification algorithms and optimization techniques to determine the most effective model for accurate and efficient virus identification.

## Problem Statement

A company has been experiencing repeated computer virus attacks over several months.  
Although the viruses have been grouped into a few known types, **identifying the virus type after an attack is time-consuming**.

To address this problem, a dataset containing:
- Extracted system and file features
- Corresponding virus type labels (target variable)

is used to build a classification system that can **predict the virus type as quickly and accurately as possible**.

## Approach

The project follows standard machine learning best practices by:
- Experimenting with multiple classification algorithms
- Evaluating baseline model performance
- Applying cross-validation for robust evaluation
- Performing feature selection to reduce dimensionality
- Using grid search for hyperparameter tuning
- Testing ensemble learning to combine model predictions

## Models Evaluated

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)
- Naive Bayes
- Voting Classifier (Ensemble)

## Optimization Techniques

- k-Fold Cross-Validation
- Feature Selection
- Grid Search Hyperparameter Tuning
- Ensemble Voting

## Key Findings

- Hyperparameter tuning significantly improves model performance
- Feature selection helps stabilize validation results
- Random Forest provides the best overall accuracy and robustness
- Ensemble voting does not outperform the strongest individual model

## Technologies Used

- Python
- scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook
