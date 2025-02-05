# NVIDIA Overvaluation Analysis

## 📌 Introduction
This project analyzes whether NVIDIA's stock is currently overvalued by comparing its fundamental indicators to macroeconomic factors. The goal is to assess if the stock price reflects its intrinsic value or if there are signs of overvaluation.

## 🎯 Objectives
- Investigate the relationship between NVIDIA's stock price and macroeconomic indicators.
- Perform fundamental valuation using financial ratios and Discounted Cash Flow (DCF) modeling.
- Identify potential market inefficiencies that could indicate a speculative bubble.

## 📊 Data Sources
- **Stock Prices & Financials**: Yahoo Finance API
- **Macroeconomic Indicators**: FRED API (Federal Reserve Economic Data)
- **Market Sentiment (optional)**: Twitter API, Google Trends

## 🏗️ Methodology
1. **Data Collection**: Gather historical stock prices, company financials, and macroeconomic data.
2. **Exploratory Data Analysis (EDA)**: Identify trends, correlations, and potential anomalies.
3. **Valuation Models**:
   - Fundamental analysis using P/E, P/S, and EV/EBITDA ratios.
   - Discounted Cash Flow (DCF) analysis to estimate intrinsic value.
4. **Machine Learning (Optional)**: Use regression models to predict stock price based on macroeconomic variables.
5. **Visualization & Insights**: Build interactive charts to present key findings.

## 🛠️ Tech Stack
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **APIs**: Yahoo Finance, FRED
- **Valuation Tools**: DCF, Financial Ratios
- **Visualization**: Plotly, Dash
- **Data Storage**: SQLite (if necessary for storing processed data)

## 📂 Project Structure
```
/ nvidia_overvaluation_analysis
│── /data               # Raw and processed data
│── /notebooks          # Jupyter notebooks for analysis
│── /scripts            # Python scripts for data collection & modeling
│── /visualizations     # Reports and dashboards
│── README.md           # Project documentation
```

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/FMPING/nvidia_overvaluation_analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run data collection script:
   ```bash
   python scripts/data_collection.py
   ```
4. Open Jupyter Notebook for analysis:
   ```bash
   jupyter notebook notebooks/eda.ipynb
   ```

## 📈 Results & Insights
TBD - This section will be updated once the analysis is completed.

---
### ✨ Future Improvements
- Implement a deep learning model to predict stock prices.
- Expand the dataset to include more companies for comparison.
- Develop a real-time dashboard for valuation tracking.

📌 **Author:** [Felipe da Silva Monteiro](https://github.com/FMPING)

