# Portfolio Risk Calculator

This project is a Python-based tool designed to evaluate and manage portfolio risk by calculating essential financial metrics. It provides investors and analysts with insights into portfolio performance, risk exposure, and return optimization using statistical methods.

---

## Features

- **Sharpe Ratio**: Measures risk-adjusted return.
- **Portfolio Volatility**: Calculates overall risk based on asset correlations and variances.
- **Value at Risk (VaR)**: Estimates potential portfolio losses at a given confidence level.
- **Data Handling**: Uses `pandas` for structured financial data management.
- **Visualization**: Leverages `matplotlib` for intuitive risk and return plots.

---

## Technologies Used

- **Python**
- **NumPy** – numerical computations
- **Pandas** – data handling and transformation
- **Matplotlib** – visualizations

---

## Project Workflow

1. **Data Preparation**: Load historical stock/ETF data into a pandas DataFrame.
2. **Return Calculation**: Compute daily returns for each asset.
3. **Portfolio Simulation**: Define portfolio weights and compute weighted returns.
4. **Risk Metrics**:
   - Calculate Sharpe Ratio for performance evaluation.
   - Estimate portfolio volatility using covariance matrices.
   - Compute Value at Risk (VaR) for downside risk analysis.
5. **Visualization**: Plot return distributions and portfolio performance trends.

---

## Visualizations

### 1. Adjusted Close Prices
Tracks the historical performance of individual assets (AAPL, GOOGL, MSFT).  
![Adjusted Close Prices](Visualization%201.png)

---

### 2. Efficient Frontier
Shows portfolio trade-offs between risk (volatility) and return.  
- **Orange X**: Portfolio with maximum Sharpe ratio.  
- **Green Diamond**: Portfolio with minimum volatility.  

![Efficient Frontier](Visualization%202.png)

---

## Potential Improvements

- Integrating live market data from APIs (Yahoo Finance, Alpha Vantage).
- Adding Monte Carlo simulations for portfolio stress testing.
- Building a simple front-end dashboard for interactive analysis.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-risk-calculator.git
   cd portfolio-risk-calculator
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run all cells line by line
4. Optional* you can change start date and end date based on the yfinance lib
