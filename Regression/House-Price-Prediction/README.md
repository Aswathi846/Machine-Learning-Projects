\# 🏠 House Price Prediction (Ames Housing Dataset)



This project implements a complete machine learning pipeline to predict residential home prices in Ames, Iowa. It focuses on extensive exploratory data analysis (EDA) and optimizing regression models.



\## 📊 Project Workflow



\### 1. Exploratory Data Analysis (EDA)

\- \*\*Visualization:\*\* Used `Seaborn` and `Matplotlib` to visualize the distribution of Sale Prices and feature correlations.

\- \*\*Handling Outliers:\*\* Identified and managed skewed data using Log-Transformations.

\- \*\*Missing Data:\*\* Used `missingno` to visualize and impute missing values across 81 features.

## 📊 Data Visualization \& Analysis



\### 1. Feature Correlations

We used a heatmap to identify which variables most strongly influence house prices.
<img width="1245" height="248" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/f03c5687-afa7-4328-ac0a-c398f4a553e9" />



\### 2. Target Variable Distribution

Before modeling, we analyzed the distribution of `SalePrice` to check for skewness.

<img width="811" height="611" alt="three_chart_plot" src="https://github.com/user-attachments/assets/318b8392-f0c2-4f8c-b8ed-672c6e4757d3" />



\### 3. Model Performance

This scatter plot shows the relationship between our predicted values and the actual house prices.

<img width="1162" height="727" alt="regression_plot" src="https://github.com/user-attachments/assets/0c14856e-0ae0-41b9-9c5c-b8ba2592cf40" />



\### 2. Feature Engineering \& Preprocessing

\- Handled categorical variables through encoding.

\- Scaled numerical features for better model convergence.

\- Performed statistical checks using Q-Q plots to ensure normality.



\### 3. Machine Learning Models

I implemented and compared several regression techniques using `scikit-learn`:

\- \*\*Linear Regression\*\*

\- \*\*Ridge \& Lasso Regression\*\* (for regularization)

\- \*\*ElasticNet\*\*

\- \*\*Hyperparameter Tuning:\*\* Optimized models using `GridSearchCV` and `RandomizedSearchCV`.



\## 🧪 Results

The final model was evaluated using \*\*RMSE (Root Mean Square Error)\*\*. The hyperparameter tuning significantly reduced the error compared to the baseline linear model.



\## ⚙️ Requirements

\- Python 3.x

\- pandas, numpy, scikit-learn, matplotlib, seaborn, scipy, missingno


