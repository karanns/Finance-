# Finance
Finance Concepts in Python


1. Value at Risk 



Value at risk is a key risk management metric used since the last two decades. 
It is the probability of loss in value of a riky portfolio/asset given a specified time period t and a confidence interval.

Parametric Method :

VaR formula for a standard normal distribution  = Mean - Zscore*stddev

Mean = 1%

ZScore = 1.65

StdDev = 1%

Var = 1% - 1.65*1%

VaR = - 0.65%

How does it work ? - Let's assume we have a probability distribution which is normally distributed.(i.e. mean = 0, std = 1)
Let's assume that our distribution has a 95% confidence interval. Since VAR is a quantile study, let's assume that at the 95% interval we have an amount of $120.
This states that there is a 5% chance that the VAR will be greater than $120 for a given period. 

Using Monte Carlo Simulation (Brownian Motion)

Monte Carlo Simulation is a method to predict the probability of different outcomes when there is an intervention of random variables.One of the most famous stochastic processes is a geometric brownian motion. Brownian motion is a random motion of particles suspended in a medium. Inside a box there are many particles that are in motion and collide with each other. The path that one of the particles chooses randomly is known as a brownian motion. In order to quantify this geometric brownian motion was introduced for a stochastic process.

For an arbitrary initial value S0 the above SDE has the analytic solution (under Itô's interpretation):

St = S0exp((μ−σ^2/2)t+σWt)


Disadvantage of the VaR Concept

Let's assume we have an outlier and the outlier falls outside the confidence interval chosen. In this case the VAR cannot factor-in this loss and it always shows the losses which occur within the confidence interval chosen/ the probability of the loss that is relevant. 

2. Basic TvM and Quantitative Methods

Covering Time Value of Money concepts like PV, FV and Net Present Value.
