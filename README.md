# SIT720 11.1HD - Heart Disease Prediction

## Project Overview

This project reproduces and extends a published machine learning study for heart-disease prediction.

The project implements six classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Naive Bayes
- K-Nearest Neighbours

A stacking ensemble is also implemented to reproduce the ensemble-learning component of the selected research study.

## Proposed Extension

The project extends the reproduced approach by introducing mutual-information-based feature selection before stacking. Candidate feature counts are evaluated using cross-validation.

## Files

- `11.1HD_Heart_Disease_Reproduction.ipynb` - Complete Python implementation and experiments.
- `Heart.csv` - Heart-disease dataset used for the implementation.
- `README.md` - Project documentation.

## Reproducibility

The notebook contains the complete preprocessing, model training, evaluation, stacking and feature-selection workflow.

## Evaluation

Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- AUC
