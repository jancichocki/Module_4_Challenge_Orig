# Financial Portfolio Performance Analysis

## Introduction
This project conducts a thorough analysis of financial portfolios including major investment firms and algorithmic trading strategies against the S&P 500 index. Using Python for data manipulation and analysis, the project evaluates the performance of these portfolios to determine which strategy outperforms the market.

## Data Sources
- **Whale Returns**: Represents the returns of major investment firms.
- **Algorithmic Trading Strategies**: Returns generated from algorithmic trading within the market.
- **S&P 500 Index**: Used as the market benchmark for comparison.

All data is processed and analyzed to extract insights into the comparative performance of each strategy.

## Objectives
- Calculate and compare daily and cumulative returns of all portfolios to the S&P 500.
- Analyze the volatility of the portfolios.
- Determine the risk of each portfolio.
- Calculate and interpret the Sharpe Ratios.
- Conduct rolling statistics analyses to understand the trends over time.

## Analysis
### Performance Analysis
- **Daily Returns**: We calculated and plotted the daily returns for all portfolios, providing insights into the daily fluctuations and potential volatility.
- **Cumulative Returns**: By calculating and plotting cumulative returns, we evaluated the overall growth of each portfolio over time. This analysis helped us identify which portfolios, if any, outperformed the S&P 500, offering a broader perspective on investment growth.

### Risk Analysis
- **Box Plots**: For each portfolio, we created box plots to visually assess the spread and central tendency of returns, highlighting outliers and volatility.
- **Standard Deviation**: We calculated the standard deviation for each portfolio to quantify the amount of variation or dispersion of returns, offering a measure of risk.
- **Risk Comparison**: By comparing these standard deviations, we determined which portfolios exhibited higher risk than the S&P 500.
- **Annualized Standard Deviation**: To account for the effect of compounding, we calculated the annualized standard deviation, providing a yearly measure of risk.

### Rolling Statistics
- **Rolling Standard Deviation**: Utilizing a 21-day window, we calculated and plotted the rolling standard deviation for all portfolios. This method helped us understand the changing risk profile over time.
- **Correlation Analysis**: Through correlation matrices, we analyzed the relationships between each stock and the S&P 500. This analysis identified portfolios that closely mimic the market's movements.
- **Rolling Beta**: Choosing one portfolio, we calculated and plotted its 60-day rolling beta with the S&P 500, assessing how the portfolio's returns moved in relation to the market.

### Exponentially Weighted Average (Rolling Statistics Challenge)
- We explored the exponentially weighted moving average (EWMA) with a 21-day half-life as an alternative to simple rolling averages. This method places greater importance on recent observations, offering a different angle on trend analysis.

### Sharpe Ratios
- **Return-to-Risk Ratio**: The Sharpe ratio, a critical metric for evaluating investment performance, was calculated for each portfolio. This ratio measures the return received for each unit of risk.
- **Visualization**: We visualized the Sharpe ratios using a bar plot, facilitating a clear comparison across all portfolios.
- **Performance Comparison**: This analysis concluded whether the algorithmic strategies managed to outperform both the market and the whale portfolios in terms of return-to-risk ratio.


## Conclusions
The analysis provides insights into which portfolios outperform the S&P 500 index and offer a higher return per unit of risk. Detailed findings will be discussed based on the calculated metrics.
