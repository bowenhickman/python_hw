# Python Class Homework & Final Project

## Overview

This repository contains two key assignments completed for my Python programming class:

1. **hw5.ipynb** – Homework 5, which focuses on practicing core Python concepts such as functions, loops, file handling, and data analysis using stock data.
2. **FINAL_PROJECT.ipynb** – Final project that analyzes and compares different trading strategies in the stock market using historical stock data.

---

## Final Project: Stock Strategy Analysis

### Description

The final project evaluates three trading strategies across ten different stocks using historical price data:

- **Buy-and-Hold Strategy**
- **Mean Reversion Strategy**
- **Simple Moving Average (SMA) Crossover Strategy**

The notebook computes key performance metrics for each approach and provides visual comparisons of cumulative returns.

### Key Features

- Backtests three strategies over the same stock universe
- Visualizes performance using `matplotlib`
- Calculates total return, average return, and volatility per stock and strategy
- Results are summarized in tables and charts

### Technologies Used

- Python (Jupyter Notebook)
- pandas
- numpy
- matplotlib

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/bowenhickman/python_hw.git
   cd python_hw
   
2. Install required libraries (if not already installed):
  pip install pandas matplotlib numpy jupyter

3. Launch Jupyter Notebook:
  jupyter notebook
  
4. Open and run the notebooks:

Open hw5.ipynb to view Homework 5

Open FINAL_PROJECT.ipynb to view the final stock strategy analysis

5. Run all cells in order for each notebook to reproduce the results

## Notes

If needed, stock data may be loaded via online sources (e.g., yfinance, CSVs) depending on how the notebooks are coded.

No external data files are currently included in the repository. If your version of the notebooks references local data, make sure to place those files in the same directory.
