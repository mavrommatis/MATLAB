# MATLAB

This directory contains several MATLAB scripts that I've written throughout the course of my Ph.D. So far, I've added the following codes:

## MCMC

This code performs Marcov Chain Monte Carlo (MCMC) sampling for Bayesian inference using uniform and/or Gaussian priors. The code estimates model parameters x given data d and the model
 
 y = f(x) + ε 

where f is the model function and ε are Gaussian errors, ε ~ N(0,Σ) with covariance matrix Σ. The function f can be either linear or nonlinear in x. In the case of Gaussian prior, we have 

x ~ N(x_p,C)

with x_p and C being the mean vector and covariance matrix for the normal distribution, respectively.
