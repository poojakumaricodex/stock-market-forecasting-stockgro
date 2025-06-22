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
└── results

## 🚀 How to Run

1. Clone this repo or open the notebook in Colab
2. Install the required libraries:
pip install -r requirements.txt

3.Run stock_forecasting.ipynb:
Load each stock’s data from data/
Forecast prices using ARIMA and Prophet
Compare performance and visualize trends
Compute RMSE, MAPE
Allocate ₹10,00,000 based on results

#Output 
![image](https://github.com/user-attachments/assets/ef248677-b055-45ca-b71c-40a5351e3624)

![image](https://github.com/user-attachments/assets/8f3870b3-b196-45fd-b07f-850cdc53aa2b)

![image](https://github.com/user-attachments/assets/253890e1-3f80-42b6-b608-da56d407bf72)


