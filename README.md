# Bike-Sharing-Case-Study

## Project Overview
This project aims to predict daily bike demand for a U.S. bike-sharing service using multiple linear regression. The analysis helps BoomBikes, a bike-sharing provider, understand key factors affecting bike rentals and prepare for post-pandemic demand.

## Problem Statement
BoomBikes experienced a significant revenue dip due to the COVID-19 pandemic. The goal is to build a predictive model to estimate bike demand and help the company optimize its business strategies to meet future demand efficiently.

## Dataset
The dataset contains daily bike demand along with features such as:
- **Weather conditions**
- **Time-related features** (season, year, month, etc.)
- **User types** (casual and registered users)

The target variable for prediction is **`cnt`**, representing the total number of daily bike rentals.

## Key Steps
1. **Data Preprocessing**: Encoding categorical variables and handling multicollinearity.
2. **Model Building**: Using multiple linear regression with the target variable `cnt`.
3. **Model Evaluation**: Evaluating model accuracy with R-squared on the test set.

## Technology Stack
- Python
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels.api`

