# 🏠 Energy Efficiency Prediction Project

This project focuses on predicting the **Heating Load** and **Cooling Load** of residential buildings based on their architectural and physical features, using machine learning techniques.

## 📌 Objective
To explore the relationship between building design parameters and energy consumption, and to build predictive models for energy efficiency. This project is intended both as a learning experience and as a portfolio project.

## 📁 Dataset
The dataset is obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency).  
It contains 768 samples and 8 input variables describing building geometry, orientation, glazing, etc.

## 🧪 Used Libraries

- `pandas` – for data manipulation
- `scikit-learn` – for building and evaluating models
- `matplotlib` & `seaborn` – for data visualization

## 🔍 Features Used
- Relative Compactness  
- Surface Area  
- Wall Area  
- Roof Area  
- Overall Height  
- Orientation  
- Glazing Area  
- Glazing Area Distribution  

In addition, some new features were engineered to test their impact:
- Wall-to-Roof Area Ratio  
- Wall-Roof Area Product  

## ⚙️ Models Applied
- Linear Regression (baseline model)  
- Random  Forest Regressor  
- Gradient Boosting Regressor  

Each model was trained and evaluated using `Mean Squared Error (MSE)` and `R² Score`.

## 📊 Visualizations
Various plots were generated to:
- Analyze the data distribution
- Compare predicted vs. actual values
- Understand feature importance

## 📦 Folder Structure
energy-efficiency-project/
│
├── data/ → contains raw dataset
├── notebooks/ → main notebook
├── images/ → visual outputs
├── models/ → saved models 
└── README.md → project documentation
