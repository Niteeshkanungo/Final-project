
# Title:
Estimating crypto currency value using Monte Carlo simulation.

# Team Member(s):
Niteesh Kanungo

Pradeep Kumar Thiagu

Himanshu Pareek

# Monte Carlo Simulation Scenario & Purpose:

In this project we are using a Monte Carlo simulation to look at the potential evolution of cryptocurrency prices over the time. We have simulated random walk to estimate the value of the crypto currency. 

Our purpose is to analyze how volatile different crypto currencies are and to estimate their prices over the next year. 

# Project at a glance

Analysis_crypto file

1. We started with collecting last year’s data from yahoo and stored every crypto-currency data into a csv file.

2. Testing the stored data by checking daily returns and calculating annual compound growth rate and volatility for each Crypto-currency.

3. Visualizing the growth of each crypto currency using line graph over the period of one year.

4. Visualizing stock daily returns for each crypto currency.

Monte_Carlo file

1. Defined Monte_Carlo_Sim function to generate Monte Carlo simulation, which generates random numbers with Geometric Brownian motion.

2. Performed 2000 simulations on each crypto currency and generated returns over investment plots for the year 2018.

3. Calculated investment value, 5% quantile, median value and 95% quantile for each crypto currency with the estimated highest return in Value.

4. The crytp currencies used in this project are: Bitcoin, Litecoin, Bitcoin Cash, Ethereum, IOTA, Ripple and Dash Coin.

# Simulation's variables of uncertainty

trials: We have tried to perform 2000 trials to get more accurate results, however the number of trials someone chooses is uncertain.

mu: mu or compound annual growth rate is calculated based on the data provided by yahoo.

sigma: The measure of Annual volatility of returns in a given period of time.

# Sources Used:
https://www.investopedia.com/articles/07/montecarlo.asp

http://www.pythonforfinance.net/2016/11/28/monte-carlo-simulation-in-python/
