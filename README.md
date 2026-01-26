House Price Prediction - Advanced Regression Techniques

This project implements a comprehensive machine learning pipeline to predict residential home prices in Ames, Iowa. Based on the popular Kaggle competition, it explores 79 explanatory variables to understand the factors that most significantly influence house values.



📌 Project Overview

The goal of this project is to predict the SalePrice of homes using advanced regression techniques. The dataset contains 1,460 training observations and 1,459 test observations, covering almost every aspect of residential properties.



🛠️ Tech Stack

Language: Python 3



Data Analysis: Pandas, NumPy



Visualization: Matplotlib, Seaborn, Missingno



Machine Learning: Scikit-Learn, SciPy



📊 Key Features of the Analysis

The project follows a rigorous data science workflow:



Missing Data Visualization: Used missingno matrices to identify and visualize null values across 81 columns.



Feature Engineering: \* Identified 43 categorical and 37 numerical features.



Handled skewed data; the SalePrice was found to be positively skewed (1.88), suggesting most houses were sold below the average price.



Statistical Analysis: Applied Pearson's correlation to find relationships between variables like OverallQual, GrLivArea, and GarageCars with the target price.



Data Cleaning: Dropped unnecessary columns like Id and imputed missing values for features like LotFrontage and GarageQual.



🚀 Getting Started

Clone the repository:



Bash

git clone https://github.com/your-username/house-price-prediction.git

Install dependencies:



Bash

pip install pandas numpy matplotlib seaborn missingno scikit-learn

Run the Notebook: Open House\_Price\_Prediction.ipynb in Jupyter or Kaggle to view the step-by-step execution.



📈 Results

The performance is evaluated using Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.



🙏 Acknowledgments

Chanakya Vivek Kapoor for the original Kaggle notebook and insights.



Kaggle for providing the "House Prices: Advanced Regression Techniques" dataset.

