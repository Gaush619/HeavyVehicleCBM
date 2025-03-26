# Predictive Maintenance Dashboard 🔧

This repository contains a **Streamlit-based Predictive Maintenance Dashboard** for monitoring and forecasting equipment health using time-series data. The tool provides actionable insights for reducing downtime and enhancing system reliability.

---

## Features 🚀

- **Dynamic Data Upload:** Upload CSV files containing time-series data for analysis.
- **Threshold Monitoring:** Detects parameter exceedances using predefined thresholds.
- **Remaining Useful Life (RUL):** Estimates RUL for critical parameters.
- **ARIMA Forecasting:** Uses `auto_arima` to forecast parameter trends and detect potential failures.
- **Maintenance Actions:** Provides specific maintenance recommendations for exceeded thresholds.
- **Interactive UI:** Built with Streamlit, featuring sliders, dropdowns, and visual feedback.

---

## Installation 🛠️

1. Clone this repository:
   ```bash
   git clone https://github.com/Gaush619/HeavyVehicleCBM
   cd HeavyVehicleCBM

   
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3. Run the Streamlit app:
   ```bash
   streamlit run main.py
