# Pairs Trading & Statistical Arbitrage (KO–PEP)

This repository implements an end-to-end statistical arbitrage strategy on Coca-Cola (KO) and PepsiCo (PEP).

## Objective
Build a realistic pairs trading pipeline including:
- Correlation screening  
- Engle–Granger cointegration test   
- Backtesting with transaction costs and slippage  
- Risk controls (daily stop-loss and max drawdown)

## Methodology
1. Download adjusted prices from **yFinance**  
2. Estimate hedge ratio via OLS  
3. Test spread stationarity using ADF  
4. Generate dynamic z-score signals  
5. Simulate trading with realistic frictions  

