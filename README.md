# Time_Series_Analysis
In this project I attempted to forecast my organization's monthly revenue for the month of July 2025, experimented with all the foundational time series concepts and the models like ARIMA, SARIMA, Prophet, Multi-series, smoothing.


# Time Series Revenue Forecasting (Company Project)

This project showcases a complete Time Series Analysis (TSA) pipeline to forecast **monthly revenue** for a healthcare-based organization (my current company). The project was done using real data (not shared here for confidentiality), and all output plots are included.

> ⚠️ **Note:** The raw data is not included in this repository due to confidentiality agreements. All plots and charts have been generated from actual data and included in the `images/` folder. Some data cells in the notebook have been commented out intentionally.

---

## 🧠 Project Overview

The goal was to forecast revenue trends across 31 therapy clinics for July 2025 using Time Series Forecasting techniques.

### ✅ Workflow Steps:

1. **Data Loading and Cleaning**
2. **Univariate Analysis**
3. **ARIMA and SARIMA Modeling**
4. **Facebook Prophet Modeling**
   - Additive Model (with Sunday as extra regressor)
   - Multiplicative Model (with Sunday as extra regressor)
5. **Final Forecasting for July 2025**
6. **Conclusions and Final Thoughts**

---

## 📊 Key Result

- **Forecasted Revenue for July 2025:** ₹1,93,58,713.47  and **the actual grossed to** ₹2,00,6,010
- The total was computed from SQL-extracted `Non_GST` revenue across all 31 centers.

---

## 🛠 Tools and Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels (for ARIMA/SARIMA)
- Prophet (by Facebook/Meta)
- MySQL Workbench (for revenue extraction)

---

## 📷 Forecasting Visuals

- all visuals present in the images folder
---

## 🧾 Final Thoughts

The model did well in approximating monthly revenue trends. Future improvements could include:

- Applying **Holt's linear smoothing** for trend capture
- **Holt-Winters smoothing** for trend + seasonality
- Experimenting with **multi-series Prophet modeling**
- Adding holidays, external regressors, or macroeconomic factors

---

## 🔧 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
