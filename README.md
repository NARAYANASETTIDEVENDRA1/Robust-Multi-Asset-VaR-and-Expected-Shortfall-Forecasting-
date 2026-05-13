# Robust Multi-Asset VaR and Expected Shortfall Forecasting

This repository contains the code, results, and report for the project :

**Robust Multi-Asset VaR and Expected Shortfall Forecasting via GJR-GARCH, Extreme Value Theory, and Vine Copula Models: Evidence from Indian Equity Markets**

This project develops a robust rolling-window framework for forecasting portfolio Value-at-Risk (VaR) and Expected Shortfall (ES). The framework is designed to overcome the limitations of traditional risk models that rely on normality assumptions and therefore may underestimate extreme losses in the presence of volatility clustering, heavy tails, and complex cross-asset dependence.

The methodology combines AR(1)–GJR-GARCH(1,1) models for conditional volatility, Extreme Value Theory (EVT) with the Generalized Pareto Distribution (GPD) for tail modelling, kernel density estimation (KDE), vine copulas for multivariate dependence modelling, and Monte Carlo simulation for portfolio risk forecasting.

A central contribution of the project is the explicit treatment of EVT threshold instability in rolling-window estimation. In some windows, no threshold satisfies standard goodness-of-fit and stability criteria for reliable GPD estimation. To address this practical issue, two fallback approaches—a KDE-based method and a model-implied (no-KDE) alternative—are developed and systematically compared. This operational problem has received relatively limited attention in the rolling-window risk forecasting literature.

The empirical study uses Indian equity data from SBI, Infosys, Hindustan Unilever (HUL), and Tata Motors listed on the National Stock Exchange of India (NSE).

## Author
N. Devendra (ME21B127)  
Indian Institute of Technology Madras

## Supervisor
Prof. Neelesh Upadhye

## Repository Contents
- `code/` – Python scripts 
- `results/` – Full outputs
- `report/` – Final report
