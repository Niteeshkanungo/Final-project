
# Title:
Estimating crypto currency value using monte carlo simulation.

# Team Member(s):
Himanshu Pareek

Pradeep Kumar Thiagu

Niteesh Kanungo

# Monte Carlo Simulation Scenario & Purpose:

In this project we are using a Monte Carlo simulation to look at the potential evolution of crypto currency prices over time. we have simulated random walk to estimate the value of the crypto currency. 

Our purpose is to analyze how volatile different crypto currencies are and to estimate their prices over the next year. 

# Project at a glance

Analysis_crypto file

1. We started with collecting last years data from yahoo and stored every crpto currency data into a csv file.

2. Testing the stored data by checking daily returns and calculating annual compound growth rate and volatility for each crpto currency.

3. Visualizing the growth of each crypto currency using line graph over the period of one year.

4. Visualizing stock daily returns for each crypto currency.

Monte_Carlo file

1. Defined Monte_Carlo_Sim function to generate monte carlo simulation, which generates random numbers with geometric brownian motion.

2. Performed 1000 simulations on each crypto currency and generated returns over investment plots for the year 2018.

3. Calculated investment value, 5% quantile, median value and 95% quantile for each crypto currency with the estimated highest return in Bitcoin (BTC).

4. The crytp currencies used in this project are: Bitcoin, Litecoin, Bitcoin Cash, Ethereum, IOTA, Ripple and Dash Coin.

5. We also optimized the code in terms of time complexity and reduced the 40 seconds of time our code took before optimization to 29 seconds. 

# Simulation's variables of uncertainty

trials: We have tried to perform 1000 trials to get more accurate results, however the number of trials someone chooses is uncertain.

mu: mu or compound annual growth rate is calcaulated based on the data provided by yahoo.

sigma: The measure of Annual volatility of returns in a given period of time.

# Sources Used:
https://www.investopedia.com/articles/07/montecarlo.asp

http://www.pythonforfinance.net/2016/11/28/monte-carlo-simulation-in-python/


