# Time Series Forecasting with Machine Learning

## 📌 Project Overview

This project focuses on **anomaly detection** and **time series forecasting** using machine learning techniques. The dataset used for this project is **AEP\_hourly.csv**, which contains hourly energy consumption data. The model leverages **XGBoost (XGBRegressor)** to predict future energy usage based on historical trends.

## 🔧 Features & Techniques

- **Data Preprocessing:**
  - Handling missing values
  - Feature engineering
  - Data normalization
- **Exploratory Data Analysis (EDA):**
  - Boxplots for hourly and monthly energy distribution
  - Time series visualization
- **Modeling with XGBoost:**
  - Hyperparameter tuning
  - Early stopping for better performance
  - Feature importance analysis
- **Evaluation Metrics:**
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared score

## 📂 Files in This Repository

- `AEP_hourly.csv` - The dataset used for training and evaluation.
- `time_series_forecasting_with_machine_learning.ipynb` - Jupyter Notebook with all the code for preprocessing, visualization, and modeling.
- `README.md` - This file, providing an overview of the project.

## 🚀 Getting Started

### 1️⃣ Install Dependencies

Make sure you have the necessary Python libraries installed:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
