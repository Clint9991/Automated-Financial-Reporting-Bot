# 📈 Automated Financial Reporting Bot

## 📌 Project Overview
Corporate finance teams waste hundreds of hours manually downloading market data, calculating moving averages, and formatting charts for executive presentations. This project is a Python-based **Automated Financial Reporting Bot** designed to eliminate that manual workflow.

By integrating directly with the Yahoo Finance API, this script extracts live stock data, processes algorithmic trading signals (Golden Cross / Death Cross), and instantly renders professional-grade data visualizations.

## 🛠️ Architecture & Technologies
* **Language:** Python
* **API Integration:** `yfinance` (Yahoo Finance API)
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`

## ⚙️ The Automation Pipeline
### 1. Live Data Extraction (API)
* Establishes a direct connection to the Yahoo Finance API.
* Automatically pulls the last 365 days of live trading data for a specified ticker (e.g., AAPL) without requiring manual CSV downloads.

### 2. Algorithmic Financial Logic
* Automatically calculates the **20-day Simple Moving Average (SMA)** and **50-day Simple Moving Average (SMA)**.
* Evaluates the intersection of these averages to generate automated `BULLISH` or `BEARISH` market tendency signals.

### 3. Automated Executive Visualization
* Uses `matplotlib` to render clean, business-ready charts that overlay the live closing price with the short-term and long-term moving averages, providing immediate visual proof of the algorithmic signal.
* <img width="1920" height="1020" alt="executive financial chart image" src="https://github.com/user-attachments/assets/b006bea3-65d3-4d69-b01f-b7fc24d5a632" />


## 📈 Business Impact
This automation transforms a multi-hour manual reporting process into a 5-second script execution, proving the value of programmatic API integration and automated financial analytics in an enterprise environment.
