# Walmart Retail Sales Forecasting

This project uses PySpark to predict Walmart's weekly sales based on historical and economic data.

## 📁 Project Structure

Walmart-retail-forecasting/
├── Data/
│ ├── features.csv
│ ├── sales.csv
│ └── stores.csv
├── Retail_Sales_Forecasting.ipynb
└── README.md


## 🔧 Technologies

- PySpark
- Google Colab or Jupyter Notebook
- GCS (Google Cloud Storage)
- Git & GitHub

## 🚀 What It Does

- Reads and joins Walmart sales, features, and store data
- Converts and assembles features for machine learning
- Trains a linear regression model
- Evaluates it using RMSE, MAE, and R²

## 📊 Model Results

- **RMSE**: 2.04e-07
- **MAE**: 2.04e-07
- **R²**: 1.0 ✅

## 📌 Run It Yourself

1. Clone this repo:
   ```bash
   git clone https://github.com/nikithavelma/Walmart-retail-forecasting.git
2. Open the notebook file: Retail_Sales_Forecasting.ipynb
3. Run it in Jupyter or Google Colab with PySpark installed.