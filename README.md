# 📈 Stock Market Forecasting using ARIMA & Prophet (StockGro Project)

This project forecasts stock prices using **ARIMA** and **Prophet** time series models. It is part of a simulation on StockGro to make smart investment decisions for a ₹10,00,000 portfolio. The goal is to identify the best-performing stocks and allocate capital based on model accuracy and trends.

---

## 🎯 Objective

- Forecast future stock prices (e.g., INFY, TCS, HDFC)
- Compare performance of ARIMA and Prophet models
- Evaluate results using RMSE and MAPE
- Allocate capital across top-performing stocks
- Visualize forecasts and model accuracy

---

## 🧠 Models Used

- **ARIMA** (Auto-Regressive Integrated Moving Average)
- **Prophet** (Facebook’s open-source time series forecasting library)
- RMSE and MAPE for model evaluation

---

## 📊 Sample Output

- 📉 Forecasted closing prices for the next 30 days
- 📊 RMSE Comparison: Prophet vs ARIMA
- 🧾 Suggested portfolio distribution (e.g., 40% INFY, 30% TCS, 30% ITC)

---

## 🧰 Tools & Libraries

- Python (Google Colab / Jupyter Notebook)
- 'pandas', 'numpy'
- 'matplotlib'. 'seaborn`
- `statsmodels' (ARIMA)
- `prophet'
- `scikit-learn' (metrics)
- `yfinance' (data optional)

---

## 🗂️ Folder Structure
stock-market-forecasting-stockgro/
│
├── stock_forecasting.ipynb # Forecasting notebook
├── requirements.txt # Libraries used
├── README.md # This file
│
├── data/
│ ├── INFY-Stock_Prices-2020_2024.csv
│ ├── TCS
│ ├── HDFC
│ └── ITC
│
└── results/
├── prophet_vs_arima.png
└── stock_allocation_pie.png
