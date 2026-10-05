# Ames Housing Price Prediction

University machine-learning regression project completed at Bocconi University (2026).

## Overview

This project builds an end-to-end regression workflow to predict residential property prices using the **Ames Housing** dataset.

The project focuses on careful preprocessing and model comparison rather than treating the dataset as a simple benchmark.

## Methods

The workflow includes:

- exploratory data analysis
- feature-specific missing-value treatment
- categorical encoding
- feature engineering
- PCA and clustering exploration
- comparison of linear, regularized and tree-based regression models
- cross-validation
- hyperparameter tuning

Models explored include Linear Regression, Ridge, Elastic Net, Random Forest, KNN, HistGradientBoosting and XGBoost.

## Result

The final tuned **HistGradientBoosting** model achieved a validation RMSE of approximately **$23.8k**.

## Technologies

Python · pandas · NumPy · scikit-learn · XGBoost · regression · feature engineering · gradient boosting

## Project focus

A central part of the project is the preprocessing logic: missing values are handled according to their meaning rather than with a single blanket rule, and model families are compared systematically before tuning the strongest candidates.

The notebook is currently being polished into a cleaner portfolio version.
