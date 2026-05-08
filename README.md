# 📊 Financial Econometrics —  Projects

**Author:** Lenon Marengwa
**Course:** Financial Econometrics (HASTS 201)

---

## Repository Overview

This repository contains two  projects completed as part of a Financial Econometrics course. Both projects apply quantitative time series methods to real equity data from Apple Inc. (AAPL) and Microsoft Corp. (MSFT), sourced from public financial markets (daily frequency, 2018–2025).

---

## Projects

### Project 1 · Best-Practices Handbook

**Dataset:** AAPL daily prices (2018–2025)

A Jupyter notebook serving as a best-practices handbook for quants on a derivatives desk. The notebook addresses four key challenges in time series modeling:

| Challenge | Focus |
|-----------|-------|
| **Multicollinearity** | Detection and mitigation strategies |
| **Skewness** | Impact on return distributions and model assumptions |
| **Sensitivity to Outliers** | Diagnosis and robust estimation approaches |
| **Overfitting** | Cross-validation and model selection techniques |

Each challenge follows a structured **7-D framework**:

```
Definition → Description → Demonstration → Diagram → Diagnosis → Damage → Directions
```

**Data Source:** Apple Inc. (AAPL) via Yahoo Finance · `yfinance` API · No local files required

---

### Project 3 · Time Series Modeling — Non-Stationarity & Equilibrium

**Datasets:** AAPL and MSFT daily prices (2018–2025)

A research paper and executable Jupyter notebook modeling non-stationarity across two co-moving equity series. The analysis covers:

| Component | Description |
|-----------|-------------|
| **Cointegration Testing** | Engle–Granger procedure to confirm a long-run equilibrium between AAPL and MSFT |
| **VECM Estimation** | Vector Error Correction Model parameter interpretation and speed-of-adjustment analysis |
| **Diagnostics & Visualisation** | Exploratory plots, residual diagnostics, regime analysis, and deployment strategy |

The same framework is applied with an extended final step:

```
Definition → Description → Demonstration → Diagram → Diagnosis → Damage → Directions → Deployment
```

**Data Source:** AAPL & MSFT via Yahoo Finance · `yfinance` API · No local files required

---

## Getting Started

All notebooks download data automatically at runtime — no CSV files need to be uploaded or manually prepared.

```bash
# Install dependencies
pip install yfinance pandas numpy matplotlib seaborn statsmodels scipy arch

# Launch Jupyter
jupyter notebook
```

> **Note:** Run cells sequentially from top to bottom. The data download cell in each notebook must execute before any modelling or visualisation cells.

---

## Repository Structure

```
├── lenonmarengwa_project_1_handbook.ipynb   # Project 1 — Best-Practices Handbook
├── Lenon_Marengwa_GWP3_FINALsub1.ipynb     # Project 3 — Non-Stationarity & VECM
└── README.md
```

---

*University of Zimbabwe · Faculty of Science · Department of Statistics*
