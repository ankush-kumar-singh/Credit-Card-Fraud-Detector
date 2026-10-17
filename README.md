
# Credit Card Fraud Detection

## Project Overview

This project focuses on exploring credit card transaction data to understand fraudulent transaction patterns and eventually build a machine learning model to detect potentially fraudulent transactions.

The main challenge is that fraudulent transactions represent only a very small proportion of all transactions, making this a highly imbalanced classification problem.

## Dataset

- **Total Transactions:** 284,807
- **Total Features:** 30 input features and 1 target column
- **Legitimate Transactions:** 284,315
- **Fraudulent Transactions:** 492
- **Fraud Rate:** Approximately 0.173%

The dataset contains anonymized features (`V1`–`V28`), transaction time, transaction amount, and a target column named `Class`.

- `Class = 0`: Legitimate transaction
- `Class = 1`: Fraudulent transaction

## Current Progress

The project is currently in the Exploratory Data Analysis (EDA) stage.

Initial observations include:

- Identified 1,081 duplicate rows for further investigation.
- Observed a substantial difference between the mean and median transaction amounts.
- Found a wide range of transaction amounts, from 0 to approximately 25,691.
- Observed that the 75th percentile of transaction amounts is approximately 77.
- Created an initial histogram to explore the distribution of transaction amounts.

These findings are preliminary and will be investigated further during the analysis.

## Project Objectives

- Understand the dataset and its underlying patterns.
- Investigate duplicate records and data quality.
- Explore transaction amount distributions.
- Compare legitimate and fraudulent transactions.
- Address the challenges of imbalanced classification.
- Build and evaluate a baseline machine learning model.
- Assess model performance using suitable classification metrics.

## Planned Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Evaluation Metrics

Accuracy alone can be misleading for highly imbalanced datasets. The planned evaluation will focus on:

- Precision
- Recall
- F1-score
- Precision-Recall curve
- Average Precision (AP)

## Current Status

**In Progress — Exploratory Data Analysis**

Model development, evaluation, and deployment will be considered after completing the data exploration stage.

## Learning Approach

This project is being developed step by step, with an emphasis on understanding the data, interpreting findings, and learning the reasoning behind each analytical and modelling decision rather than simply implementing code.

## Dataset Source

[Kaggle — Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
