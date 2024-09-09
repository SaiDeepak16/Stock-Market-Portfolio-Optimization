# Stock Market Portfolio Optimization

This project involves optimizing a stock portfolio using historical data to achieve the best possible risk-adjusted return. By analyzing stock price trends, calculating expected returns and volatilities, and determining correlations, this project aims to provide an optimal allocation strategy for selected stocks.

## Goal
The goal of this project is to identify the portfolio with the highest **Sharpe ratio**, indicating the best risk-adjusted return. The project provides insights into the stocks' performance and offers a clear allocation strategy to achieve long-term investment objectives.

## Stocks Analyzed
- **HDFCBANK.NS**
- **INFY.NS**
- **RELIANCE.NS**
- **TCS.NS**

## Key Features
1. **Adjusted Close Price Over Time**  
   The adjusted close prices of the stocks from July 2023 to July 2024 are analyzed, highlighting TCS as having the highest prices, followed by RELIANCE, INFY, and HDFCBANK. TCS and RELIANCE show upward trends, indicating strong performance, while HDFCBANK and INFY are more stable.

2. **Adjusted Close, Moving Averages, and Volume Traded**  
   Moving averages provide insights into price trends and recoveries, while the volume graphs show significant trading activity, particularly for HDFCBANK and RELIANCE in early 2024.

3. **Distribution of Daily Returns**  
   Daily returns for all stocks show approximately normal distributions, centred around zero. INFY and RELIANCE have wider distributions, reflecting higher volatility compared to HDFCBANK and TCS.

4. **Correlation Between Stocks**  
   INFY and TCS have a high positive correlation (0.71), while HDFCBANK and RELIANCE show a moderate correlation (0.32). Low correlations between certain stocks suggest potential diversification benefits.

## Expected Returns and Volatility
- **INFY**: Highest expected return (32.11%) and highest volatility (22.24%)
- **RELIANCE**: Expected return of 21.34%, volatility of 21.44%
- **TCS**: Expected return of 30.55%, volatility of 20.73%
- **HDFCBANK**: Lowest expected return (4.64%) and volatility (21.65%)

## Optimization Strategy
The optimization involves generating a series of random portfolio weights and calculating the expected return and volatility for each. These portfolios are then plotted to visualize the **efficient frontier**, which represents the portfolios offering the highest expected returns for given levels of risk.

Portfolios on the leftmost edge of the frontier provide the highest risk-adjusted returns, represented by their Sharpe ratio.

## Next Steps
- **Generate Random Portfolios**: Create random portfolio weights and calculate their expected returns and volatilities.
- **Visualize Efficient Frontier**: Plot these portfolios and highlight the ones with the highest Sharpe ratio.
- **Optimize Portfolio**: Maximize the Sharpe ratio to determine the optimal allocation for the stocks in the portfolio.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SaiDeepak16/Stock-Market-Portfolio-Optimization.git
