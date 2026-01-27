# 🏠 House Price Prediction (Ames Housing Dataset)

This project implements a complete machine learning pipeline to predict residential home prices in Ames, Iowa. It focuses on extensive exploratory data analysis (EDA) and optimizing regression models.

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- **Visualization:** Used `Seaborn` and `Matplotlib` to visualize the distribution of Sale Prices and feature correlations.
- **Handling Outliers:** Identified and managed skewed data using Log-Transformations.
- **Missing Data:** Used `missingno` to visualize and impute missing values across 81 features.

### 2. Feature Engineering & Preprocessing
- Handled categorical variables through encoding.
- Scaled numerical features for better model convergence.
- Performed statistical checks using Q-Q plots to ensure normality.

### 3. Machine Learning Models
I implemented and compared several regression techniques using `scikit-learn`:
- **Linear Regression**
- **Ridge & Lasso Regression** (for regularization)
- **ElasticNet**
- **Hyperparameter Tuning:** Optimized models using `GridSearchCV` and `RandomizedSearchCV`.

## 🧪 Results
The final model was evaluated using **RMSE (Root Mean Square Error)**. The hyperparameter tuning significantly reduced the error compared to the baseline linear model.

## ⚙️ Requirements
- Python 3.x
- pandas, numpy, scikit-learn, matplotlib, seaborn, scipy, missingno
