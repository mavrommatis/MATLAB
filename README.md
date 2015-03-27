# Bayesian inference

## Markov chain Monte Carlo (mcmc.m)

This code implements a [Markov chain Monte Carlo](http://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo) (MCMC) sampling method using the [Metropolis-Hastings](http://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm) algorithm. The code allows for  uniform or Gaussian priors in the unknown model parameters. The code estimates model parameters x given data d and the model
 
 y = f(x) + ε 

where f is the model function and ε are Gaussian errors, ε ~ N(0,Σ) with covariance matrix Σ. The function f can be either linear or nonlinear in x. The code allows for Gaussian prior distribution in the model parameters,  

x ~ N(x_p,C)

with x_p and C being the mean vector and covariance matrix, respectively.
