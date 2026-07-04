# 🏋️ Body Performance Prediction

## 📌 Project Overview

This project develops an intelligent machine learning system for analyzing human body performance using biological and physical measurements.

The project combines:

- Exploratory Data Analysis (EDA)
- Classification
- Regression
- Feature Engineering
- Model Evaluation

The objective is to predict a person's fitness class and estimate their broad jump distance using body measurements and fitness indicators.

---

# Objectives

The project addresses two machine learning tasks.

## 1️⃣ Classification

Predict the body performance class:

- Class A (Highest Performance)
- Class B
- Class C
- Class D (Lowest Performance)

---

## 2️⃣ Regression

Predict:

- Broad Jump Distance (cm)

using the remaining body measurements.

---

# Dataset

The dataset contains

- **13,393 observations**
- **12 features**

### Demographics

- Age
- Gender

### Body Composition

- Height (cm)
- Weight (kg)
- Body Fat (%)

### Vital Signs

- Systolic Blood Pressure
- Diastolic Blood Pressure

### Fitness Measurements

- Grip Force
- Sit and Bend Forward
- Sit-ups Counts
- Broad Jump Distance

### Target Variable

Classification Label

- A
- B
- C
- D

---

# Project Workflow

## 1. Data Preparation

- Data Cleaning
- Duplicate Removal
- Missing Value Checking
- Outlier Detection
- Data Validation

---

## 2. Exploratory Data Analysis

Performed statistical and visual analysis including

- Distribution Analysis
- Correlation Matrix
- Feature Relationships
- Class Distribution
- Fitness Metrics Analysis

---

## 3. Feature Engineering

- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Data Transformation

---

## 4. Machine Learning Models

### Classification

- Neural Network (MLPClassifier)
- Support Vector Machine (RBF Kernel)
- Decision Tree

### Regression

- Neural Network Regressor
- K-Nearest Neighbors Regressor

---

## 5. Model Evaluation

Classification Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Regression Metrics

- MAE
- MSE
- RMSE
- R² Score

Validation

- Train/Test Split
- K-Fold Cross Validation

---

# Key Insights

✔ Broad Jump is the strongest predictor of body performance.

✔ Grip Strength significantly contributes to predicting athletic performance.

✔ Sit-ups Count strongly correlates with higher fitness levels.

✔ Individuals with lower body fat percentages generally achieve higher fitness classes.

✔ Neural Networks and Support Vector Machines achieved the highest classification performance.

✔ Decision Trees provide interpretable results while maintaining acceptable accuracy.

✔ Model performance remained stable across multiple train/test splits, demonstrating good generalization.

---

# Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Structure

```
Body-Performance-Prediction
│
├── Notebook
├── Dataset
├── Images
└── Reports
```

---

# Future Improvements

- Hyperparameter Optimization
- XGBoost
- LightGBM
- CatBoost
- SHAP Explainability
- Streamlit Deployment

---

# Author

Ahmed Abdelaziz

AI Graduate

Microsoft Certified: PL-300 Power BI Data Analyst

Data Analyst | Machine Learning Enthusiast
