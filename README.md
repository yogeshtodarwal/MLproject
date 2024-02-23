# Student Performance Indicator Project

## Overview
The "Student Performance Indicator" project is a comprehensive machine learning project designed to predict student academic performance based on various factors. The model takes into account a range of features, including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch (type of lunch program)
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

Utilizing the features, aim is to provide insights into how different factors affect student outcomes and identify potential areas for intervention.

The data is obtained from https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977


## Models Tested
explored a variety of machine learning models to ensure robust and accurate predictions. The models tested include:

- **Linear Regression**: A baseline model for predicting continuous variables.
- **Lasso**: Linear Regression with L1 regularization to prevent overfitting.
- **Ridge**: Linear Regression with L2 regularization for high-dimensional data.
- **K-Neighbors Regressor**: A non-parametric method that uses neighboring points for predictions.
- **Decision Tree**: A model that splits the data into branches to make predictions.
- **Random Forest Regressor**: An ensemble of Decision Trees for more accurate and stable predictions.
- **XGBRegressor**: An implementation of gradient boosted decision trees designed for speed and performance.
- **CatBoosting Regressor**: A gradient boosting framework that handles categorical features directly.
- **AdaBoost Regressor**: An adaptive boosting method that combines multiple weak learners into a strong one.

## Evaluation Metrics
To assess the performance of models, the following metrics were used:

- **Root Mean Squared Error (RMSE)**: Measures the model's prediction error.
- **Mean Absolute Error (MAE)**: Averages the absolute differences between predicted and actual values.
- **R2 Score**: Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Project Goals
This project serves as an end-to-end toy project for learning purposes, covering all components of the ML pipeline, from data preprocessing and model selection to evaluation and interpretation. Through this project, aim is to:

- Understand the impact of various factors on student performance.
- Identify the most predictive features of academic success.
- Develop a reliable model for predicting student outcomes.
