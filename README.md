# NVIDIA Overvaluation & Macroeconomic Regime Analysis

This project analyzes whether NVIDIA (NVDA) stock valuation can be explained by macroeconomic conditions or if it has structurally decoupled from traditional economic drivers.

The analysis focuses on **valuation sustainability across macro regimes**, rather than short-term price prediction.

---

## 🎯 Research Question

**Is NVIDIA overvalued relative to macroeconomic fundamentals, or is its valuation justified under specific macro regimes (rates, liquidity, growth)?**

Key angles:
- Does NVDA valuation expand disproportionately during low-rate / high-liquidity regimes?
- Which macro variables explain **valuation multiple expansion**, not just price movement?
- Are current valuation levels statistically outside historical macro-consistent ranges?

---

## 📊 Methodology

### 1. Data Collection
- **Stock data:** NVDA price & valuation metrics (Yahoo Finance)
- **Macro indicators:**
  - GDP (US & Global) — FRED
  - CPI (US) — FRED
  - Federal Funds Rate — FRED
  - S&P 500 Index — Yahoo Finance
  - Industrial Production — World Bank
  - Semiconductor Investment — BEA

### 2. Feature Engineering
- Returns, volatility, drawdowns
- Valuation multiples (P/E, normalized P/E)
- Macro lags (3M, 6M, 12M)
- Regime flags (high vs low rates, inflationary vs disinflationary)

### 3. Modeling
- Correlation & stability analysis
- Multivariate regression (OLS / regularized)
- Regime-based valuation comparison
- Time-series forecasting (ARIMA / Prophet) as supporting evidence

---

