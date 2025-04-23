# Spaceship-Titanic_kaggle_3%

This repository contains my solution to the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) competition on Kaggle.

## Overview
The task in this competition was to predict whether passengers were transported to a different dimension, based on their features such as age, spending, destination, and more. I used several machine learning techniques, data preprocessing, and feature engineering methods to build my solution.

## Solution Approach

- **Data Preprocessing**: Handled missing values, created new features, and transformed categorical variables using one-hot encoding.
- **Feature Engineering**: Split the 'Cabin' column, created new features such as `TotalSpent`, `AgeGroup`, and used domain-specific knowledge to derive more insights.
- **Model**: I used the **LightGBM** classifier with hyperparameter tuning. The pipeline included preprocessing steps such as scaling numerical features and encoding categorical ones.
- **Model Evaluation**: Used accuracy as the evaluation metric, and tuned the model based on the leaderboard results.

## Performance
I ranked in the top **5%** of the leaderboard, achieving a significant performance improvement through various iterative steps in the model training process.

## Tools and Libraries
- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Seaborn**, **Matplotlib** for visualization
- **sklearn**
- **LightGBM** for classification
- **SHAP** for model interpretability

## Getting Started
To run the solution locally, clone the repository and install the dependencies:
```bash
git clone https://github.com/Blase-AI/Spaceship-Titanic_kaggle_3-.git
cd spaceship-titanic
pip install -r requirements.txt
