# Nvidia Overvaluation Analysis and Macroeconomic Correlation

## Project Overview
This project analyzes the overvaluation of Nvidia (NVDA) stock in relation to key macroeconomic indicators. By leveraging historical stock price data and economic metrics, we aim to uncover patterns, correlations, and insights into whether Nvidia's growth is driven by fundamentals or speculative trends.

## Objectives
- Assess the correlation between Nvidia's stock performance and macroeconomic indicators.
- Evaluate the sustainability of Nvidia's market valuation.
- Use statistical and machine learning models to predict potential future trends.

## Data Sources
- **Stock Data**: Yahoo Finance API (`yfinance`)
- **Macroeconomic Indicators**:
  - GDP (USA & Global) - [FRED API](https://fred.stlouisfed.org/)
  - Inflation (CPI USA) - FRED API
  - Federal Funds Rate - FRED API
  - S&P 500 Index - Yahoo Finance API
  - Industrial Production (USA) - [World Bank API](https://databank.worldbank.org/source/world-development-indicators)
  - Semiconductor Investment - [BEA](https://www.bea.gov/)

## Tools & Technologies
- **Python** for data analysis and modeling
- **Pandas, NumPy** for data manipulation
- **Matplotlib, Seaborn** for visualization
- **Statsmodels, Scikit-learn** for regression and statistical modeling
- **Facebook Prophet, ARIMA** for time-series forecasting
- **Jupyter Notebook** for exploratory analysis
- **GitHub** for version control

## Project Structure
```
├── data/               # Raw and processed data
├── notebooks/          # Jupyter notebooks for analysis
├── src/                # Python scripts for data processing & modeling
├── results/            # Final reports and visualizations
├── README.md           # Project documentation
├── requirements.txt    # Python dependencies
└── .gitignore          # Files to ignore in Git
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nvidia_macro_analysis.git
   cd nvidia_macro_analysis
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

## Key Findings (So Far)
- Nvidia's stock price has increasingly decoupled from GDP trends, indicating a shift towards innovation-driven valuation.
- Federal Reserve interest rate decisions have a strong correlation with Nvidia's stock volatility.
- The P/E ratio of Nvidia is significantly above historical averages, suggesting a potential overvaluation.

## Next Steps
- Implement a deeper machine learning model to forecast Nvidia's price trends.
- Incorporate alternative macroeconomic indicators such as semiconductor industry investments.
- Expand analysis to include sentiment data from financial news sources.

## Contributions
Feel free to contribute by submitting pull requests or reporting issues!

## License
This project is licensed under the MIT License.

---

### 🚀 Let's explore Nvidia's valuation beyond the hype! 📊
