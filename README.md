# Stock Drawdown Analysis

This project involves analyzing the drawdown of a specified stock over a given period. The drawdown is a measure of the peak-to-trough decline in the stock's price during that period. The project identifies the worst drawdown, the period during which it occurred, and visualizes the stock price alongside the drawdown period.

## Key Features:
- **Stock Data Retrieval:** Utilized the `yfinance` library to download historical adjusted close prices for the specified stock.
- **Drawdown Calculation:** Calculated the cumulative maximum of the stock price to identify drawdowns, and determined the worst drawdown during the specified period.
- **Period Analysis:** Identified the start and end dates of the worst drawdown and calculated the duration of this period.
- **Data Visualization:** Plotted the stock price over time, highlighting the drawdown period on the chart with vertical lines.

## Key Skills:
- **Programming:** Python (`yfinance`, `Matplotlib`, `Pandas`)
- **Data Analysis:** Drawdown calculation, cumulative maximum, period analysis
- **Financial Metrics:** Drawdown analysis, peak-to-trough measurement
- **Data Visualization:** Time series plotting, highlighting significant periods

## Python Libraries:
- **yFinance** (`import yfinance as yf`)
  - For accessing financial data from Yahoo Finance
- **Matplotlib** (`import matplotlib.pyplot as plt`)
  - For data visualization and plotting
  - **Matplotlib Ticker** (`import matplotlib.ticker as mtick`)
    - For customizing axis ticks and labels
  - **Matplotlib Dates** (`import matplotlib.dates as mdate`)
    - For formatting dates on the x-axis in plots
- **Datetime** (`import datetime as dt`)
  - For handling dates and times
- **Pandas** (`import pandas as pd`)
  - For reading, manipulating, and analyzing data
- **NumPy** (`import numpy as np`)
  - For numerical computing and handling arrays

-------------------

<img width="589" alt="image" src="https://github.com/user-attachments/assets/b1a67e28-4f6f-42ad-9aa9-7c485a89bbd2">
