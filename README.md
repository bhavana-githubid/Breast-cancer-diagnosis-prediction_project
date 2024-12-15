# Breast Cancer Diagnosis Prediction

This project leverages machine learning techniques to predict breast cancer diagnosis (malignant or benign) using clinical data. It demonstrates the implementation of classification algorithms and evaluates their performance to identify the best model for accurate predictions.

## Overview
Breast cancer diagnosis is a crucial task in medical science, and early detection can save lives. This project builds a predictive model to classify breast cancer using labeled data and machine learning techniques.

## Dataset
The dataset used for this project contains labeled data with features extracted from digitized images of breast tissue samples. 

### Key Attributes:
- **ID Number**: Unique identifier for each observation
- **Diagnosis**: Malignant (M) or Benign (B) (target variable)
- **Features**: Measurements like radius, texture, perimeter, area, smoothness, compactness, symmetry, etc., computed for each sample.

## Features
The project includes the following steps:
1. **Data Preprocessing**: 
    - Handling missing values
    - Scaling and normalizing features
2. **Exploratory Data Analysis (EDA)**: 
    - Visualizing relationships and distributions
    - Correlation analysis
3. **Model Implementation**:
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - Support Vector Machine (SVM)
    - Naive Bayes
    - KNN
4. **Model Evaluation**:
    - Accuracy
    - Precision, Recall, F1-score

## Modeling Approach
The project follows these steps:
1. **Data Loading**: Load and preprocess the dataset.
2. **Exploratory Analysis**: Perform EDA to understand the data better.
3. **Feature Selection**: Identify and use the most relevant features for modeling.
4. **Model Training and Tuning**: Train multiple models and fine-tune their hyperparameters.
5. **Evaluation**: Use evaluation metrics to compare model performances.

## Results
- The models achieved the following accuracies:
  - **Logistic Regression**: ~97%
  - **Decision Tree**: ~95%
  - **Random Forest**: ~96%
  - **SVM**: ~98%
  - **Naive Bayes**: ~96%
  - **KNN**: ~95%

SVM emerged as the top-performing model with high accuracy.


