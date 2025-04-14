# TIME-SERIES-FORECASTING-AND-TREND-ANALYSIS-ON-NYC-TAXI-DATA
# 📊 Time Series Forecasting Web Application

This Streamlit web application is designed to allow users to **upload a CSV file containing time series data**, visualize trends, decompose the series into components, and forecast future values using popular time series models.

---

## 🔍 What This App Does

### 1. **CSV Upload and Preprocessing**
- Users can upload their own time series data in `.csv` format.
- After upload, the user selects:
  - A **date column** (used as index)
  - A **target column** (values to forecast)
- Data is cleaned and visualized via an interactive line chart.

### 2. **Time Series Decomposition**
- The app supports both **Additive** and **Multiplicative** decomposition.
- Users specify a seasonal period (e.g., 7 for weekly, 12 for monthly seasonality).
- Outputs four components:
  - Observed
  - Trend
  - Seasonality
  - Residuals

### 3. **Forecasting Models**
- Users can forecast future values using one of three models:
  - **ARIMA** – Best for linear, short-term forecasting
  - **ETS (Exponential Smoothing)** – For stable seasonal patterns
  - **Prophet** – For long-term trends and holiday-aware forecasting
- Forecast horizon can be set between 7 and 60 steps.

### 4. **Evaluation Metrics**
- The app splits the data for training and testing.
- Evaluation metrics are displayed:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)

---

## 💼 Use Cases
- Transportation demand prediction (e.g., NYC taxi trips)
- Sales and revenue forecasting
- Public health and hospital admissions planning
- Climate and weather trends
- Any time series data with trend or seasonality

---


---


---

## 🧠 Built With
- Python
- Streamlit
- Pandas, Numpy
- Matplotlib
- Statsmodels (ARIMA, ETS)
- Prophet (by Meta)
- Scikit-learn (for metrics)

---

## 👨‍💻 Author
Developed for forecasting projects and data visualization experiments using real-world time series datasets.
