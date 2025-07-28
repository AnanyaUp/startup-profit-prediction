# startup-profit-prediction
 Predict startup profit based on R&amp;D, Administration, and Marketing spend using a multiple linear regression model trained on the 50_Startups dataset. Includes full EDA, model training, performance evaluation, and visualizations with Python, Pandas, and Scikit-learn

 # Startup Profit Prediction using Multiple Linear Regression

This project builds and evaluates a **Multiple Linear Regression** model to predict the **profit of a startup** based on its **R&D Spend**, **Administration Cost**, and **Marketing Spend**. It includes full **exploratory data analysis (EDA)**, **model training**, and **performance evaluation** using Python libraries such as `Pandas`, `Scikit-learn`, and `Seaborn`.

---

## Project Highlights

- Multiple Linear Regression using `scikit-learn`
- EDA including correlation heatmaps, pairplots, and outlier detection
- Model evaluation using **R² Score, MAE, MSE, RMSE**
- Business use case: Forecasting startup profitability
- Interpretable ML with visualizations

---

## Dataset Overview

- **Dataset Name:** 50_Startups.csv
- **Features:**
  - R&D Spend
  - Administration
  - Marketing Spend
- **Target Variable:**
  - Profit

---

## Model Performance

| Metric       | Value         |
|--------------|---------------|
| R² Score     | 93.21% (Test) |
| MAE          | ₹6.6 Lakhs    |
| MSE          | ₹652 Crores   |
| RMSE         | ₹8.07 Lakhs   |

> Achieved high accuracy, showing R&D spend has the strongest impact on profit.

---

### Correlation Heatmap
Shows R&D has the strongest positive correlation with Profit.

### Boxplots & Distplots
Used to detect outliers and skewness in feature distributions.

### Pairplot
Explores relationships among features and target.

---

## Tech Stack

-  Python
-  Pandas, NumPy
-  Matplotlib, Seaborn
-  Scikit-learn

---
