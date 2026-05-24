# To Boost or Not to Boost: XGBoost and DCC-GARCH Integration for Mean-Variance Portfolio Optimization

This repository contains the empirical framework and implementation code for studying the integration of Machine Learning-based return predictions and Econometric dynamic risk estimations to enhance Markowitz's traditional Mean-Variance portfolio framework.

## 📌 Project Overview
The core objective of this study is to examine whether integrating **XGBoost (Extreme Gradient Boosting)** for asset return prediction and **DCC-GARCH (Dynamic Conditional Correlation - Generalized Autoregressive Conditional Heteroskedasticity)** for time-varying covariance estimation yields superior portfolio risk-adjusted returns (e.g., higher Sharpe/Sortino ratios, lower maximum drawdown) compared to traditional historical Mean-Variance baselines.

---

## 📂 Repository Structure

The project is structured into modular components mapping out the data pipelines, quantitative modeling steps, and final analysis:

* `MVP_Optimization_XGB+DCC.ipynb` – The master notebook implementing the complete empirical strategy. Integrates data processing, XGBoost/DCC-GARCH model coupling, monthly rebalancing optimization, and backtesting performance scoring.
* `MACRO_DATA/` – Contains macroeconomic variables for the predictive models.
* `XGB_model/` – asset return predictions model via XGBoost.
* `DCC_model/` – covariance predictions model via DCC-GARCH.
* `fig/` – Exported visualization plots (e.g., cumulative returns comparison, efficient frontiers, asset allocation weights over time).
* `Portfolio_data.xlsx` – The primary structured financial dataset containing historical asset prices/returns and required features.

