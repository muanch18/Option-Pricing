## Option-Pricing
Created in Spring 2022. We formatted a report that demonstrates three different models to price European call options: Black-Scholes, Monte Carlo Simulations, and a 
Multi-layer Perceptron. 

### Procedure
We used historical Apple call option data to train and test the MLP Model and to test the accuracy against the results of the Black Scholes and Monte Carlo Simulation models.
The method of measuring the accuracy involved the Root Mean Square Error for each of the respective models using the historical data.


### Overview of Results
Based on the RMSE, we found the Multi-layer Perceptron to be the most accurate. It is also important to note that all models were the least accurate for at the money options. 
This is based off the large sample size of the ATM options and them naturally being the most sensitive to price movements. 
