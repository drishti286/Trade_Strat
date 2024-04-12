# Trade_Strat
A trading strategy made using technical indicators like MACD and Stochastic Oscillator using python language. 


**Introduction:**
In this project, I've developed an equity trading strategy using Python that generates buy and sell signals based on a combination of price, volume, and technical indicators. The aim is to create a strategy that can outperform the market by intelligently utilizing available data.

**Data Collection and Processing:**
- Utilized the yfinance package to download historical stock data from Yahoo Finance at a daily interval.
- Focused on close price and volume data for analysis.

**Strategy Development:**
Rather than relying solely on traditional technical indicators, I incorporated a blend of techniques including:
1. Moving Average Convergence Divergence (MACD): A trend-following momentum indicator.
2. Stochastic Oscillator: Used to identify overbought and oversold conditions.
3. Volume Indicator: Analyzed volume spikes to gauge market sentiment.

**Implementation:**
1. Developed Python code to calculate MACD, Stochastic Oscillator, and volume indicators.
2. Established buy and sell rules based on a combination of these indicators.
3. Used position variables to track open or closed positions.
4. Plotted buy and sell points on a chart to visualize trading signals.

**Performance Evaluation:**
1. Calculated portfolio returns, drawdowns, Sharpe ratio, etc.
2. Generated a CSV file containing buy and sell points, position status, and portfolio value.
3. Computed summary statistics including strategy return, annualized return, benchmark return, number of trades executed, max drawdown, win ratio, loss-making trades, largest loss-making trade, largest profit-making trade, and daily return.

**Conclusion and Insights:**
Through this project, I gained insights into the effectiveness of combining multiple indicators for trading strategies. I learned about technical indicators and how it is implemented. However, further refinement and backtesting across various market conditions are necessary for robustness.


Overall, this project provides a framework for developing and evaluating equity trading strategies using Python, with a focus on incorporating diverse data sources and indicators for improved decision-making.
