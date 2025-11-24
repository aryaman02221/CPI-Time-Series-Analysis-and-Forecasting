# 📈 CPI Time Series Analysis & Forecasting  
**Course AAT Project – Time Series Analysis (TSA)**  

This project presents an end-to-end analysis of India’s Consumer Price Index (CPI) using monthly data from MoSPI. CPI is a widely used economic indicator for inflation, making it suitable for time-series tasks involving decomposition, stationarity testing, and forecasting. The dataset shows clear trend–seasonality patterns, enabling comparison of multiple forecasting models.

---

## 📝 Project Overview

The study focuses on understanding CPI behaviour and generating reliable forecasts.  
The objective includes:

- Cleaning month-wise CPI data and forming a continuous monthly time series  
- Performing EDA, decomposition, and irregular component analysis  
- Checking for white-noise and non-stationarity using ADF & KPSS  
- Reducing non-stationarity through log transforms and differencing  
- Building and comparing forecasting models such as **ARIMA**, **SARIMA**, and **Holt-Winters**  
- Visualizing forecast performance against actual values  

---

## 🧭 Phase I – Preliminary Analysis (CO1)

- Cleaned dataset (resolved missing months)  
- Converted year–month table into a proper monthly index  
- Time-series visualizations  
- Boxplots and rolling statistics  
- Seasonal decomposition (Additive, Multiplicative, STL)  
- Residual diagnostics (Ljung–Box test)  
- Stationarity testing (ADF + KPSS)  
- Log transformation and differencing  

---

## 🔮 Phase II – Forecasting Models (CO2)

Implemented forecasting models:

- **ARIMA / SARIMA**  
- **Holt-Winters Exponential Smoothing**  
- (Optional) Prophet / Fourier Seasonal Models  

Each model was evaluated based on:  
- MAE  
- RMSE  
- Forecast-vs-actual comparison  
- Residual behaviour  

Final selection was based on error metrics and visual accuracy.

---

## 📂 Repository Structure

│── data/
│ └── Dataset.xlsx # CPI dataset (MoSPI)
│
│── notebooks/
│ ├── Phase_I.ipynb # Decomposition + diagnostics
│ └── Phase_II.ipynb # Forecasting models
│
│── results/
│ ├── decomposition_plots/
│ ├── forecast_plots/
│ └── metrics.csv
│
│── README.md

---

## 🔗 Dataset Source

Ministry of Statistics and Programme Implementation (MoSPI), Government of India.

---

## 🧑‍💻 Technologies Used

- Python 3  
- Pandas  
- NumPy  
- Statsmodels  
- Matplotlib  
- Prophet (optional)  

---

## 📬 Contact  
For academic queries, feel free to open an issue in this repository.
