# Real Estate Price Prediction Project

## Overview
This project focuses on predicting real estate prices using machine learning techniques. The dataset contains information about various factors influencing real estate prices, such as floor area, lease commencement date, location, and more. The predictive models include Linear Regression, Decision Tree Regression, and Random Forest Regression.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Data Preprocessing](#data-preprocessing)
    1. [Data Cleaning](#11-data-cleaning)
    2. [Feature Selection](#12-feature-selection)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Outlier Detection and Treatment](#outlier-detection-and-treatment)
5. [Feature Engineering](#feature-engineering)
6. [Machine Learning Models](#machine-learning-models)
    1. [Model Selection](#51-model-selection)
    2. [Model Training and Evaluation](#52-model-training-and-evaluation)
    3. [Hyperparameter Tuning](#53-hyperparameter-tuning)
7. [Model Comparison and Visualization](#model-comparison-and-visualization)
8. [Model Serialization](#model-serialization)
9. [Model Testing](#model-testing)
10. [Future Steps](#future-steps)
11. [Dependencies](#dependencies)
12. [Conclusion](#conclusion)

## Project Structure

### 1. Data Preprocessing
#### 1.1 Data Cleaning
Checked and addressed missing values in the dataset.

#### 1.2 Feature Selection
Chose relevant columns for further analysis and model training.

### 2. Exploratory Data Analysis (EDA)
Explored data distribution, outliers, and relationships between variables using visualizations like box plots, histograms, Q-Q plots, and correlation matrices.

### 3. Outlier Detection and Treatment
Identified outliers using box plots, applied Z-score and IQR methods, and removed outliers based on IQR for better distribution.

### 4. Feature Engineering
Encoded categorical variables to numerical representations and standardized numerical features for improved model training.

### 5. Machine Learning Models
#### 5.1 Model Selection
- Linear Regression: Simple linear regression model.
- Decision Tree Regression: Tree-based regression model.
- Random Forest Regression: Ensemble learning regression model.

#### 5.2 Model Training and Evaluation
Split the dataset into training and testing sets. Used metrics such as MAE, MSE, RMSE, and R^2 Score for model evaluation.

#### 5.3 Hyperparameter Tuning
Performed grid search for optimal hyperparameters in Decision Tree and Random Forest models.

### 6. Model Comparison and Visualization
Compared models based on evaluation metrics and visualized model predictions using scatter plots.

### 7. Model Serialization
Saved the best Random Forest model using pickle.

### 8. Model Testing
Tested the model with sample data to ensure predictions on new, unseen data.

## 10. Future Steps
- Deployment: Explore deployment options for the trained model in a real-world setting.
- Continuous Improvement: Refine models, explore additional features, and update the model with new data for improved accuracy.

## 11. Dependencies
- Python: 3.6 or higher
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, pickle.

## 12. Conclusion
This project provides a comprehensive pipeline for predicting real estate prices. The chosen machine learning models, after careful evaluation and hyperparameter tuning, demonstrate their effectiveness in capturing the underlying patterns in the dataset. The documentation serves as a guide for understanding the project structure, methodologies, and future steps.
