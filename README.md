# riskPremiaHarvester

Edge comes from mandated selling of bonds after they are no longer considered investment grade by institutional investors which lowers the fair value of said bonds 

Harvested by comparing FALN (iShares Fallen Angels Bond ETF) against HYG and LQD ETFs

Rolling Sharpe ratio, but out-of-sample evaluation exhibits a Sharpe of 1.3


The strategy will:

Download historical data for FALN, HYG, and LQD
Calculate credit spreads
Generate trading signals based on z-scores
Calculate strategy returns
Display performance metrics
Show visualizations

The strategy generates signals based on:
Long when the spread is wide (z-score > 1)
Short when the spread is narrow (z-score < -1)
Neutral otherwise

Performance metrics include:
Annualized Return
Annualized Volatility
Sharpe Ratio
Sortino Ratio
Maximum Drawdown
