# Project Introduction

In this project, I aim to optimize a portfolio of stocks within the electric vehicle sector, leveraging historical stock data and modern portfolio optimization techniques. The EV sector has seen a massive transformation over the past decade, shifting from a niche market to a major player in the global automotive industry. Driven by advances in technology, environmental concerns, and government policies/subsidies, the EV market has seen drastic growth. According to the International Energy Agency (IEA), global electric car stock surpassed 10 million in 2020, a significant increase from just 17,000 electric cars on the world’s roads in 2010. This rapid expansion presents both opportunities and challenges for investors who want to capitalize on the sector's potential while managing associated risks.

## Stock Selection

**I will focus on a selection of prominent EV-related stocks: **

Tesla (TSLA)

Ford (F)

ON Semiconductor (ON)

Li Auto (LI)

NIO Inc. (NIO)

General Motors (GM)

XPeng Inc. (XPEV)

These companies represent a mix of established automotive companies transitioning to electric products/services and also innovative startups in new technologies and market approaches.

## Project Structure:

First, I'll collect historical stock price data for the selected companies over the past ten years using the yfinance library. This data will be used to calculate daily returns and assess the performance of a naively weighted portfolio. This initial step will provide a benchmark for comparison.

Next, I'll apply portfolio optimization techniques using the PyPortfolioOpt library. This involves calculating the expected returns and covariance matrix of the stock returns, which are crucial inputs for constructing an optimized portfolio. The optimization process will aim to maximize the [Sharpe ratio](https://www.investopedia.com/terms/s/sharperatio.asp), a measure of risk-adjusted return.

Finally, I'll visualize the performance of both the naive and optimized portfolios through cumulative return plots and compare key quantitative metrics, such as annualized return and volatility. This comparison will highlight the benefits of optimization and provide insights into the trade-offs between risk and return in the EV sector. 

## GOAL: 

This project will demonstrate how modern portfolio theory can be applied to improve investment strategies in the dynamic industry of electric vehicles.

## SUMMARY OF RESULTS: 

With tools like the Sharpe ratio, Efficient Frontier, and Covariance Shrinkage, the optimized portfolio was able to increase returns from 21% to 28% (7% improvement) over the ten years, while decreasing volatility by 2%.
