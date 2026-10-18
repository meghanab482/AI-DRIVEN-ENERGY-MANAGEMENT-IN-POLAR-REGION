# ❄️ Polar Research Station: AI-Powered Microgrid Energy Management System

An advanced, interactive microgrid energy-management and telemetry system designed for extreme polar environments (Arctic and Antarctic research stations). It leverages machine learning to forecast energy demand, optimizes renewable generation (solar/wind) against battery storage and diesel backups, and provides real-time decision support through an interactive Jupyter dashboard.

## 🚀 Key Features

* **AI Demand Forecasting:** Uses a Machine Learning Regressor (`scikit-learn`) trained on environmental telemetry to predict short-term station load and heating demands dynamically.
* **Blizzard Risk Assessment:** Integrates an AI classification model to evaluate 48-hour structural blizzard probabilities based on wind gusts, visibility, and snowfall.
* **Live Weather Integration with Failover:** Automatically fetches real-time meteorological data via the Open-Meteo API, with a seamless offline fallback to simulated historical polar datasets.
* **Smart Energy Dispatch & Optimization:** Manages battery state-of-charge (SOC) preservation floors, diesel backup generation, and demand-side management (load shedding).
* **Interactive Dashboard UI:** Built with `ipywidgets` and `Plotly` to provide real-time control, visual monitoring of power generation vs. consumption, and operational status tracking.

## 🛠️ Technology Stack

* Python (v3.8+)
* Jupyter Notebook / Jupyter Lab
* Requests
* Pandas
* NumPy
* Scikit-Learn (`scikit-learn`)
* Ipywidgets & IPython.display
* Plotly
* Functools (`lru_cache`)
