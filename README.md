# ☀️ IE Sustainability Datathon 2025: Solar Optimization for CO₂ Reduction

## 📍 Project Overview

In the 2025 IE Sustainability Datathon, our team tackled a real-world challenge posed by Repsol: **how can industrial plants maximize solar self-consumption and reduce CO₂ emissions through intelligent forecasting and battery optimization?**

We developed a complete solution that:
- Forecasts maximum solar generation using ML
- Optimizes battery usage for self-consumption or carbon impact
- Quantifies avoided CO₂ emissions (direct and lifecycle)


## 👥 Team

Ricardo Urech, Blanca Burgaleta, Ana Cortés, Vibhushan Balaji, Tomás Valbuena, Dhabia Saad


## 📁 Dataset

The dataset used in this project was provided by Repsol as part of the IE Sustainability Datathon 2025 and contains confidential industrial and meteorological data.

Due to confidentiality agreements, the raw data cannot be shared publicly. However, all results, code logic, and methodologies are fully available in this repository.

📌 Data Description:
- Hourly solar generation and electricity consumption data from an industrial facility
- Meteorological inputs from four nearby weather grid points
- Time-aligned to the Europe/Madrid timezone
- Used for: predictive modeling, battery optimization, and CO₂ impact analysis


## 🚀 Key Highlights

- 📈 **XGBoost model (weekday-only)** achieved **MAE = 4.91 kWh**
- ⚡ Optimization increased solar self-consumption (Ra) from **82.36% to 85.26%**
- 🌍 CO₂ optimization avoided **+5,000 gCO₂eq** more emissions
- 🧪 Lifecycle emissions analysis showed **124,028 gCO₂eq avoided**


## 🔍 Project Structure
- README.md >>> Project overview, goals, methods, and results (this file)
- EDA and Feature Engineering.ipynb >>> Exploratory data analysis, cleaning, and feature engineering for ML modeling
- Solar Prediction Model.ipynb >>> Objective 1: Predictive modeling of maximum solar generation (Random Forest & XGBoost)
- Battery Optimization.ipynb >>> Objective 2: Battery usage optimization to improve self-consumption and reduce CO₂ emissions


## 🧰 Tools & Technologies

- Python (Pandas, Numpy, Statsmodels, Scikit-learn, XGBoost, SciPy, Seaborn, Matplotlib, Optimization_engine)
- Jupyter Notebooks
- Git and GitHub for version control


## 📄 License

This project is for educational and professional showcase purposes. Please contact for collaboration.
