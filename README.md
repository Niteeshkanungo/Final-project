
# Title:
Estimating crypto currency value for the next 2 years using monte carlo simulation.

# Team Member(s):
Himanshu Pareek

Predeep Kumar Thiagu

Niteesh Kanungo

# Monte Carlo Simulation Scenario & Purpose:

In this project we are using a Monte Carlo simulation to look at the potential evolution of crypto currency prices over time. we have simulated random walk to estimate the value of the crypto currency. 

We will be using a Monte Carlo simulation to look at the potential evolution of asset prices over time, assuming they are subject to daily returns that follow a normal distribution (n.b. as we know, asset price returns usually follow a distribution that is more leptokurtic (fat tailed) than a normal distribution, but a normal distribution is often assumed for these kind of purposes). This type of price evolution is also known as a “random walk”.

We are trying to put risk in an investment in a single value (VaR) by simulating random market conditions and calculating loss for each market condition and then aggragating the results to establish a profile of the market's risk.

# Hypothesis before running the simulation:

Stock price evolution can be simulated by geometric brownian motion (GBM), which means we are assuming that all available public information is incorporated in the current price of the stock and the next price is conditionally independent of the past price.

# Simulation's variables of uncertainty

Startprice: It is the initial value of the stock before any market movements.

trials: We are trying to categorize results based on number of times the simalation is performed and analyze the value of VaR accordingly.


# Sources Used:
https://www.investopedia.com/articles/07/montecarlo.asp

http://www.pythonforfinance.net/2016/11/28/monte-carlo-simulation-in-python/


