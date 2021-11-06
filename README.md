# chiteki
time series DB, analytics, twap, vwap, backtesting

Time-Weighted Average Price (TWAP)
An asset’s time-weighted average price (TWAP) is the measure of an asset’s average price over a predetermined period of time. TWAP can be calculated for any specified time duration. TWAP trading algorithms seek to optimize a trade’s average price while executing over a specified time period. This is generally used to execute large orders that are expected to have significant market impact.

Volume-Weighted Average Price (VWAP)
An asset’s volume-weighted average price (VWAP) is calculated by taking the average of every trade in a specified time period. Each trade is weighted proportionally to the quantity of the order. In regard to a specific order that is filled at multiple prices, the VWAP can be calculated on aggregate by looking at net quantity and net price.


Objective
1. to evaluate a particular set of execution whether it is underperformed or overperformed based on TWAP and VWAP algo trading strategy
2. to consume a raw data set of past trading history, forming a time series over executed prices and volume
