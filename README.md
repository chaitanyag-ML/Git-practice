**Student Performance Prediction using Machine Learning**

**Project Overview**

This project predicts student academic scores based on study habits and academic factors using regression models.
It demonstrates an end-to-end machine learning workflow using Linear Regression and Random Forest Regressor.

**Problem Statement**

Accurately predicting student performance helps educators identify learning gaps early and provide timely academic support.
This project uses machine learning to predict final student scores using historical academic data.

**Machine Learning Approach**

The project includes:
Data loading and preprocessing
Feature scaling (for Linear Regression)
Training regression models
Model comparison and evaluation
Saving trained models for future predictions

**Technologies Used**

Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Joblib

**Tools:** Jupyter Notebook, Git

**Dataset Description**

The dataset contains the following features:

Feature	Description
study_hours	Average daily study hours
attendance	Attendance percentage
previous_score	Score in previous examination
assignments_completed	Number of assignments completed
final_score	Target variable (Predicted score)

**Models Implemented**
    **Linear Regression**
Applied feature scaling using StandardScaler
Suitable for predicting continuous outcomes
Simple and interpretable baseline model

  **Random Forest Regressor**
Ensemble-based regression model
Captures non-linear relationships
No feature scaling required
Provides feature importance

**Model Evaluation Metrics**
Both models are evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

The performance of Linear Regression and Random Forest Regressor is compared to select the best-performing model.

**Model Saving**
Trained models are saved using joblib
Scaler is saved for consistent preprocessing during inference
