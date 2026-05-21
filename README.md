# AI-Based Air Quality Prediction System

## Overview

This project is a Machine Learning based Air Quality Prediction System developed using Python and Scikit-learn. The project focuses on preprocessing environmental datasets, performing exploratory data analysis, training machine learning models, and evaluating predictive performance for air pollution analysis.

The system predicts pollution levels using multiple regression algorithms and visualizes model performance using graphs and statistical plots.

---

# Objectives

- Clean and preprocess environmental datasets
- Handle missing values and outliers
- Train multiple machine learning models
- Compare model performance
- Predict pollution levels
- Visualize prediction accuracy
- Understand supervised learning workflows

---

# Features

## Data Preprocessing
- Missing value handling
- Duplicate removal
- Label encoding
- Date conversion
- Feature selection

## Machine Learning Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Model Evaluation
- MAE
- MSE
- RMSE
- R² Score

## Visualizations
- Model comparison charts
- Actual vs Predicted plots
- Feature importance graphs
- Residual plots
- Correlation heatmaps

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Joblib | Model Saving |

---

# Dataset Information

Dataset contains:
- Air quality measurements
- Country information
- City information
- Pollution metrics
- Environmental statistics
- Time-series records

---

# Machine Learning Workflow

## Step 1: Data Collection
Load environmental dataset using Pandas.

## Step 2: Data Cleaning
- Remove duplicates
- Handle missing values
- Encode categorical columns
- Convert datetime columns

## Step 3: Feature Engineering
Prepare input features and target variable.

## Step 4: Train-Test Split
Split dataset into:
- Training data
- Testing data

## Step 5: Model Training
Train:
- Linear Regression
- Decision Tree
- Random Forest

## Step 6: Model Evaluation
Evaluate models using:
- RMSE
- R² Score
- MAE
- MSE

## Step 7: Visualization
Generate:
- Feature importance charts
- Model comparison graphs
- Residual analysis
- Prediction analysis

---

# Folder Structure

```bash
air-quality-ml-project/
│
├── dataset/
│   └── waqi-covid19-airqualitydata-2026Q2.csv
│
├── visualizations/
│   ├── actual_vs_predicted.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── model_comparison.png
│   └── residual_plot.png
│
├── models/
│   ├── decision_tree_model.pkl
│   ├── linear_regression_model.pkl
│   └── random_forest_model.pkl
│
├── predictive_model.py
├── processed_ml_dataset.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/GoutamNandhen/air-quality-ml-project.git
```

## Navigate to Project Folder

```bash
cd air-quality-ml-project
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Project

```bash
python predictive_model.py
```

---

# Output Files

The project generates:

- Trained ML models (.pkl)
- Processed dataset
- Visualization charts
- Performance graphs

---

# Sample Insights

- Best performing ML model
- Most influential environmental features
- Pollution prediction trends
- Residual error distribution
- Correlation between variables

---

# Future Enhancements

- Streamlit dashboard
- Real-time AQI prediction
- Deep Learning models
- XGBoost implementation
- Interactive visualization
- Deployment on cloud

---

# Learning Outcomes

This project helped in understanding:

- Supervised Learning
- Regression Algorithms
- Model Evaluation
- Feature Engineering
- Data Visualization
- Environmental Analytics
- Machine Learning Workflow

---

# Conclusion

This project demonstrates how Machine Learning can be applied to environmental datasets for pollution prediction and analytics. The system combines preprocessing, modeling, evaluation, and visualization into a complete end-to-end predictive analytics solution.

---

# Author

Goutam Nandhen
B.Tech CSE (Data Science)