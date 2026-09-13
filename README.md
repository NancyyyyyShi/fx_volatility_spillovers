# Cross-Market Volatility Transmission into Foreign Exchange Markets

This repository contains the Python code used for my MSc dissertation, **"Cross-Market Volatility Transmission into Foreign Exchange Markets: A Comparison of Linear and Information-Theoretic Causality Measures."**

## Code Structure

The analysis is organised into four Jupyter notebooks:

- `01_Data_Import_Preparation.ipynb`  
  Imports and cleans the raw financial-market data and constructs the variables used in the subsequent analysis.

- `02_EDA.ipynb`  
  Performs exploratory data analysis, volatility modelling, stationarity diagnostics, and preliminary lead-lag analysis.

- `03_Synthetic_Data.ipynb`  
  Implements the synthetic data experiments used to validate and compare Granger causality and Transfer Entropy under known data-generating processes.

- `04_Empirical_Results.ipynb`  
  Implements the main empirical analysis, including Granger causality and Transfer Entropy tests of directional cross-market volatility transmission.

## Data

The empirical analysis uses daily financial-market data from Bloomberg covering 2015–2024.

The underlying Bloomberg data are not included in this repository due to data licensing restrictions.

## Software

The analysis is implemented in Python using Jupyter notebooks.
