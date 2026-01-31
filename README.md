<h1 align="center">📈 Statistical Population Modeling & Forecasting</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <img alt="Python" src="https://img.shields.io/badge/Python-NumPy%20%7C%20SciPy%20%7C%20Matplotlib-yellow" />
  <img alt="Modeling" src="https://img.shields.io/badge/Model-Logistic%20Growth-green" />
  <img alt="Analysis" src="https://img.shields.io/badge/Analysis-Statistical-blue" />
</p>

> 📊 **A statistical modeling project focused on population dynamics using a logistic growth model.**  
The project applies numerical methods to historical population data, calibrates model parameters, validates predictions against observed data, and produces long-term forecasts.

---

## 🏠 Overview

This project develops a logistic population growth model using historical discrete population data.  
The methodology follows a full modeling lifecycle: numerical approximation, parameter estimation, model calibration, validation, and forecasting.

Multiple historical time windows are analyzed to assess model stability and sensitivity to calibration periods.

---

## 🧠 Methodology

- Numerical approximation of population growth rates using **central finite differences**
- Transformation and analysis of the ratio \( P'(t) / P(t) \) to identify a logistic relationship
- Parameter estimation via **linear regression / numerical calibration**
- Numerical solution of the resulting differential equation
- Model validation through comparison with historical observations (1990–2010)
- Long-term population forecasting (up to 2040)
- Sensitivity analysis through recalibration on different historical periods

---

## 🔍 Investigations

### Investigation A: Long Historical Period
- Calibration using early population data (1800–2010)
- Identification of increasing model underestimation after the mid-20th century
- Analysis of structural limitations due to changing growth dynamics

### Investigation B: Recalibrated Model
- Model recalibration using modern-era data
- Improved prediction accuracy and reduced relative error
- Assessment of parameter stability across time windows

### Investigation C: World Population Forecast
- Application of the methodology to global population data
- Estimation of logistic parameters for world population growth
- Forecast of global population for the year 2040

---

## 💻 Tech Stack

- **Python**
  - NumPy
  - SciPy
  - Matplotlib
- **Jupyter Notebook / Google Colab**
- Git / GitHub for version control

---

## 📊 Results & Visualization

The project includes:
- Scatter plots of transformed variables
- Linear approximation of growth-rate relationships
- Time-series comparisons between model predictions and real data
- Error analysis across multiple decades

(Plots are generated directly within the notebook.)

---

## ⚠️ Notes & Limitations

The model makes simplifying assumptions inherent to logistic growth and does not account for:
- Economic factors
- Demographic structure
- Policy changes or geopolitical shocks

As a result, long-term forecasts should be interpreted as **theoretical projections** rather than precise predictions.

---

## 🛠️ How to Run the Project

Clone the repository:

```bash
git clone https://github.com/Iasminaaaaa/Logistic-Modeling-of-Population-Data.git
```

Open the notebook in Jupyter or Google Colab, then run all cells sequentially.
