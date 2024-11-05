# MLP Dimensionality Reduction Analysis

## Project Overview
This project analyzes the impact of dimensionality reduction using Principal Component Analysis (PCA) on a Multi-Layer Perceptron (MLP) classifier’s performance. The analysis includes exploratory data analysis (EDA), data preprocessing, model training, hyperparameter tuning, and comparison of model performance before and after PCA.

## Contents
- **Basic EDA:** An initial examination of data structure, missing values, distributions, and feature relationships through visualizations like pair plots and correlation matrices.
- **Model Training and Evaluation:** 
  - Split dataset for supervised learning.
  - Trained an MLP classifier on the original dataset.
  - Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix.
  - Tuned hyperparameters using GridSearchCV to enhance model performance.
  - Applied PCA for dimensionality reduction and trained a second MLP classifier on the transformed data.
- **Findings and Conclusions:** 
  - Evaluated the trade-offs between dimensionality reduction and model accuracy.
  - Concluded that PCA slightly reduced accuracy by 2.88%, emphasizing a balance between dimensionality reduction benefits and performance.

## Key Results
- Original MLP model accuracy: ~69.65%
- PCA-transformed model accuracy: Slight decrease (~2.88%)
- Insightful comparison showing the effects of dimensionality reduction on model accuracy.

## Future Directions
Further exploration could include cross-validation, other dimensionality reduction techniques, and alternative models to refine results.

---
