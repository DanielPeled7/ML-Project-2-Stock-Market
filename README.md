# ML-Project-2-Stock-Market
Data Science project for stock market analysis and prediction using machine learning.
# Predicting 10% Stock Gains Within 30 Days

## Data Access

The dataset is not included directly in this repository due to size and/or access limitations.
גש
Expected dataset:
- A pre-breakout stock snapshot dataset
- Time range: 2015–2025
- Target column: `gain_10pct_30d`

## Project Overview

This project builds a supervised machine learning model to predict whether a stock will gain at least 10% within the next 30 trading days.

The full project overview and methodology are available in:

`ML_project__report.pdf`

## Main Notebook

The full reproducible pipeline is available in:

`Kairognos_ML_Full_Project_v2.ipynb`

## Objective

The machine-learning task is binary classification:

- Positive class: stock gained at least 10% within 30 trading days
- Negative class: stock did not reach the 10% target

## Workflow

1. Data loading and preprocessing
2. Exploratory Data Analysis
3. Time-based train / validation / test split
4. Imbalance treatment comparison
5. Model comparison
6. Feature engineering
7. Threshold tuning
8. Final test evaluation


## Final Result

The best-performing model was:

**Class-weighted Logistic Regression**
