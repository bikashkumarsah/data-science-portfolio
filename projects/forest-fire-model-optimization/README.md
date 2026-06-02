# Optimizing Forest Fire Damage Prediction

This project improves a baseline model for predicting forest fire damage using feature engineering, imputation, and validation.

## Problem

Predict forest fire damage area from weather and fire-condition features while handling skewed target behavior.

## Methods

- Explore the target distribution and apply a log transform
- Engineer seasonal features
- Impute missing values with KNN imputation
- Use sequential feature selection
- Compare regularized regression models with cross-validation

## Skills Demonstrated

- Regression modeling
- KNN imputation
- Feature engineering
- Sequential feature selection
- Cross-validation
- Ridge and Lasso regression

## Dataset

- `../../dataset/fires.csv`

## Files

- [analysis.ipynb](analysis.ipynb): full notebook analysis

## What This Shows

This project demonstrates model iteration beyond a first baseline, including preprocessing decisions and validation-driven model selection.
