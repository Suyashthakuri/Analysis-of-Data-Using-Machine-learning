# 🏡 Predicting Airbnb Listing Prices in Melbourne, Australia

### 📌 Problem Statement

In this Kaggle-style regression challenge, we were tasked with predicting the daily rental prices of Airbnb listings in Melbourne using structured property data. The goal was to minimize prediction error while exploring the features that influence pricing, such as room type, location, amenities, and review statistics.

### 🎯 Objective

Build a supervised machine learning model to predict `price` (a continuous target) using features from the dataset. The model is evaluated using **Mean Absolute Error (MAE)** to reflect real-world pricing accuracy.

### 🛠️ Step-by-Step Process

1. **Exploratory Data Analysis (EDA)** – Identified distributions, correlations, and outliers
2. **Data Cleaning** – Removed nulls, outliers, duplicates, and formatted columns
3. **Feature Engineering** – Created new variables and applied transformations (log pricing, dummy variables)
4. **Model Selection** – Trained and evaluated: Linear Regression, Decision Trees, Random Forests, and XGBoost
5. **Hyperparameter Tuning** – Used GridSearchCV to optimize model parameters
6. **Evaluation** – Compared models on MAE and interpreted feature importances

### ✅ Results Summary

| Model           | MAE (on Test Set) |
|----------------|------------------|
| Linear Regression | ~67.2           |
| Decision Tree     | ~52.4           |
| Random Forest     | ~47.1           |
| **XGBoost**       | **~43.8**       |

### 📊 Insights & Takeaways

- Log-transformation of price reduced skew and improved accuracy
- Review-related features were strong predictors of price
- Ensemble models (Random Forest, XGBoost) outperformed simple linear models
- MAE was preferred for its direct interpretability (dollar error)

### ▶️ How to Run

1. Clone the repository
2. Install dependencies via `pip install -r requirements.txt`
3. Open the notebook: `Group-Project-S1-2025.ipynb`
4. Execute all cells to reproduce the analysis and results

### 👥 Contributors

- Suyash Khand Thakuri  
