# Heavy Equipment Price Prediction

## Overview

This project predicts the sale prices of heavy equipment using machine learning. It focuses on data preprocessing, feature engineering, model evaluation, hyperparameter tuning, and ensemble learning.

The project was developed as part of an academic machine learning project based on a Kaggle competition.

## Problem Statement

Predict the sale price of used heavy equipment from its transaction details, equipment characteristics, and related features.

## Approach

The notebook follows these main steps:

1. **Exploratory Data Analysis (EDA):** Examine the target variable, feature distributions, and data quality.
2. **Feature Engineering:** Create transaction date features, estimate equipment age, extract information from model numbers, and transform operational hours.
3. **Preprocessing:** Handle missing values and encode categorical features.
4. **Validation:** Use a temporal train-validation split to evaluate model performance.
5. **Model Training:** Establish baselines using Linear Regression, Random Forest, XGBoost, and LightGBM.
6. **Hyperparameter Tuning:** Compare selected configurations to improve validation performance.
7. **Ensembling:** Combine XGBoost and LightGBM predictions and optimize their relative weights.
8. **Prediction:** Generate predictions for the competition test data.

## Evaluation Metric

The project uses **Root Mean Squared Logarithmic Error (RMSLE)** for validation.

The recorded validation RMSLE was approximately **0.2627**. This is a local validation result, not a claim about the final Kaggle leaderboard score.

## Repository Contents

- `heavy_equipment_price_prediction.ipynb` — Notebook containing the analysis, feature engineering, model experiments, evaluation, and prediction workflow.

## Requirements

The notebook uses Python and common data science libraries, including:

- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- XGBoost
- LightGBM

## How to Run

1. Clone or download this repository.
2. Obtain the competition dataset from its original source, subject to its terms of use.
3. Place the required data files in the locations expected by the notebook, or update the file paths.
4. Install the required Python libraries.
5. Run the notebook from top to bottom.

**Note:** The dataset is not included in this repository.

## Key Learning Outcomes

- Building a complete tabular machine learning workflow
- Performing feature engineering on structured data
- Evaluating models with a time-aware validation strategy
- Comparing baseline models against tuned models
- Using gradient boosting and prediction ensembling

## Disclaimer

This is an academic machine learning project. Validation performance may vary depending on the data split, environment, and library versions.

