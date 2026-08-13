# Predict Bike Sharing Demand with AutoGluon

A machine learning regression project completed as part of the Udacity Machine Learning Fundamentals Nanodegree.

## Project Overview

This project uses AutoGluon to predict bike-sharing demand from historical rental and environmental data.

The project follows a complete machine learning workflow:

- Exploratory Data Analysis (EDA)
- Feature engineering
- Automated model training with AutoGluon
- Model comparison
- Hyperparameter tuning
- Kaggle evaluation

## Models

The project experimented with:

- LightGBM
- Neural Networks
- LightGBM + Neural Networks ensembles

## Results

The initial model achieved a Kaggle RMSE of **1.80870**.

Through feature engineering and hyperparameter tuning, the performance improved substantially.

| Experiment | Kaggle RMSE |
|---|---:|
| Initial model | 1.80870 |
| Feature engineering | 0.67806 |
| LightGBM | 0.57451 |
| LightGBM + Neural Networks | 0.47889 |
| **Best model** | **0.46291** |

The best configuration used AutoGluon's `high_quality` preset with hyperparameter optimization and achieved a **Kaggle RMSE of 0.46291**.


## Tools & Technologies

- Python
- AutoGluon
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- AWS SageMaker Studio
- Kaggle

## Files

- `predict-bike-sharing-demand-with-autogluon.ipynb` — Complete project notebook
- `report.md` — Detailed project report

## Learning Outcomes

This project provided practical experience with automated machine learning, regression, feature engineering, model evaluation, and hyperparameter optimization using AutoGluon.

## Program

**AWS Machine Learning Fundamentals Nanodegree — Udacity**
