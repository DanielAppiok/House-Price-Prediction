# House-Price-Prediction

#  House Price Prediction - Random Forest Model

This repository contains a professional-grade machine learning project that predicts house prices using a Random Forest Regressor. The project follows industry best practices for data science workflows including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment.

##  Project Objective

To build a robust, accurate, and explainable house price prediction model using the Kaggle [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) dataset. The primary goal is to support real estate stakeholders with reliable price estimates based on property characteristics.

---

##  Key Features

- Cleaned and preprocessed raw housing data
- Handled missing values and categorical encoding
- Applied log transformation on target (`SalePrice`) to normalize skew
- Engineered meaningful features (e.g., total square footage, age of house)
- Trained and tuned a **Random Forest Regressor** using `GridSearchCV`
- Evaluated using **RMSE, MAE, and R²**
- Built an easy-to-use **Streamlit app** to upload CSVs and predict prices

---

## 📊 Model Performance

| Metric     | Value         |
|------------|---------------|
| RMSE       | 33,398.05     |
| MAE        | 17,579.79     |
| R² Score   | 0.8546        |

