# Loan Prediction Machine Learning Project

## Overview

This project applies machine learning to a loan dataset to solve two financial prediction tasks:

1. Predicting client loan approval status
2. Predicting the maximum loan amount for approved clients

## Research Questions

### Case Study A: Loan Approval Classification

Does machine learning have the potential to assist bankers and finance analysts in predicting which client can be approved a loan?

### Case Study B: Maximum Loan Amount Regression

Does machine learning have the potential to assist bankers in predicting the maximum loan amount offered to approved clients?

## Project Files

| File | Description |
|---|---|
| `Notebook1_w1954095_20220967.ipynb` | Data exploration, cleaning, preprocessing, and feature preparation |
| `Notebook2_w1954095_20220967.ipynb` | Classification models and evaluation |
| `Notebook3_w1954095_20220967.ipynb` | Ensemble learning and regression models |
| `_w1954095_20220967_Santosh_Manoharadas.docx` | Final analysis report |

## Main Tasks

## 1. Loan Approval Status Prediction

The classification task predicts whether a loan application should be approved or rejected.

Models used:

- Logistic Regression
- K-Nearest Neighbours
- Naive Bayes

Main preprocessing steps:

- Missing value handling
- Outlier treatment
- Categorical encoding
- Feature scaling using `StandardScaler`
- Train-test split with stratification

Evaluation metrics used:

- Recall
- Precision
- F1-score
- AUC-ROC

Accuracy was not used as the main metric because the dataset was imbalanced.

Best classification model:

```text
K-Nearest Neighbours (KNN)
