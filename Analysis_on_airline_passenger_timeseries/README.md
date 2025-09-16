# Analysis on Airline Passenger Time Series

This repository contains a time series analysis and forecasting project using the classic *Airline Passengers* dataset. The goal is to explore patterns, test stationarity, and build forecasting models (ARIMA, SARIMA) to predict future passenger counts.

---

## 📁 Repository Structure

```
Analysis_on_airline_passenger_timeseries/
├── airline_passenger_timeseries.csv    # raw dataset (monthly passenger counts)
├── eda_airline_analysis.ipynb           # original notebook with EDA + modeling
├── eda_airline_analysis_updated.ipynb   # updated notebook (frequency settings, comparison ARIMA vs SARIMA, etc.)
├── README.md                            # this file
```

---

## 🧮 Key Steps & Contents

1. **Exploratory Data Analysis (EDA)**  
   - Plotting the time series  
   - Observing trend, seasonality, variance  
   - Decomposing the series (multiplicative model)  

2. **Stationarity Testing**  
   - Augmented Dickey–Fuller (ADF) test on the original series  
   - Log transformation and ADF test  
   - First differencing of log-transformed data and ADF test  

3. **Model Building**  
   - Non-seasonal ARIMA on log-transformed data (d = 0)  
   - Seasonal ARIMA (SARIMA) to account for yearly seasonality  

4. **Model Comparison & Evaluation**  
   - Using AIC / BIC for model selection  
   - Residual diagnostics  
   - Forecasts plotted and compared  

---

## ✅ Findings (Summary)

- The original time series has a strong upward trend, evident seasonality (period = 12 months), and increasing variance.  
- The ADF tests show that the original series is non-stationary, log transformation helps, but still not enough to achieve stationarity at the 0.05 significance level. Differencing (especially seasonal) is required.  
- Non-seasonal ARIMA (on log data without differencing) performs significantly worse than a properly specified SARIMA model that captures both non‑seasonal and seasonal differencing and seasonal AR/MA components.

---

## 📦 How to Run

1. Clone the repository.  
   ```bash
   git clone https://github.com/vritik907/Data-Analysis.git
   cd Data-Analysis/Analysis_on_airline_passenger_timeseries
   ```

2. Make sure you have required libraries installed (e.g. `pandas`, `numpy`, `statsmodels`, `matplotlib`).  
   ```bash
   pip install pandas numpy matplotlib statsmodels
   ```

3. Open the notebooks (either `eda_airline_analysis_updated.ipynb` or the original) in Jupyter or JupyterLab to run them.  

4. To reproduce everything, run all cells in the updated notebook.  

---

## 📚 Further Ideas

- Explore automatic model selection (`auto_arima`) or other forecasting frameworks (Prophet, ets, etc.).  
- Examine other transformations (Box‑Cox) or handle outliers.  
- Try seasonal differencing (lag = 12) explicitly if not already.  
- Evaluate forecast accuracy using other metrics (MAE, MAPE, etc.).  

---

## 📝 License

This project is for educational/demonstration purposes. Feel free to fork and extend!

---

## 👤 Author

- **Ritik Verma**  
- Contact / More work: github.com/vritik907  
