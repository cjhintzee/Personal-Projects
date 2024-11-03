This is my third personal project on algorithmic trading. 

My strategy for this project is to calculate the beta of a portfolio of mega-cap tech stocks ("Mag 7 Mega Cap Tech Stocks") relative to a benchmark (the QQQ index) using linear regression. 
Subsequently, implement a hedging strategy by shorting QQQ to neutralize market risk and longing my portfolio, with a rebalancing period of 30 days.

The strategy:
1.	Calculate beta of portfolio relative to benchmark using Linear Regression (Ordinary Least Squares)
2.	With the beta value, calculate the long/short ratio = 1/beta
3.	Allocate respective long/short portfolio size using the long/short ratio, and determine position size of each Mag 7 stock based on vol-weightage
4.	Rebalance every 30 days, and repeat steps 1-3.
