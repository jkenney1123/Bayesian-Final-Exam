# Bayesian Data Analysis Final Exam

For the deployed html website use the following link
https://jkenney1123.github.io/Bayesian-Final-Exam/

# Weibull Model with Conjugate Prior Problem 1
## Objective
This project aims to provide a comprehensive understanding of Bayesian inference applied to the Weibull model, leveraging conjugate priors and real-world data to draw meaningful conclusions.
## Project Overview
This project focuses on the application of the Weibull distribution, particularly with a conjugate prior approach, to model the lifetimes of equipment or parts. The Weibull distribution is widely used in reliability engineering and failure analysis.
## Questions
### Question 1.1
- Demonstrate that the Gamma distribution is the conjugate prior for the Weibull(2) distribution and derive the posterior distribution.
### Question 1.2
- Derive the marginal distribution for a set of data points assumed to be independently sampled from the Weibull(2) distribution.
### Question 1.3
- Use a Gamma prior distribution to model the lifetime of gears, based on the observed data and prior knowledge. Obtain and graph the prior density, and justify its reasonableness.
### Question 1.4
- Analyze observed gear lifetime data to find and graph the posterior distribution. Calculate the posterior mean, variance, and a 95% posterior interval for the Weibull parameter θ using both analytical and numerical methods.

# Bayesian Change-Point Model Analysis for Coal Mining Disaster Data
## Objective
The objective of this project is to fit a hierarchical change-point model to analyze the number of coal mining disasters in Great Britain from 1851 to 1962. Our analysis aims to identify potential shifts in disaster occurrence rates and to estimate the posterior distributions of the parameters involved.
## Project Overview
Welcome to the repository for our Bayesian Change-Point Model analysis for coal mining disaster data. This project aims to model and analyze the number of coal mining disasters in Great Britain from 1851 to 1962 using a hierarchical change-point model. Below is a summary of our key analyses and methodologies:
## Key Questions and Analyses
1. **Model Fitting**:
- We fit a hierarchical change-point model to the coal mining disaster data, assuming a fixed change-point at year 1890.
- The model uses non-informative priors for parameters related to disaster occurrences.
2. **Gibbs Sampling**:
- We implemented a Gibbs sampler to derive the posterior distributions of parameters θ, λ, and the ratio R = θ/λ.
- The summary includes histograms, kernel density estimates, means, standard deviations, and quantiles.
- Additionally, we discuss convergence diagnostics and tools used to ensure the MCMC has reasonably converged.
3. **Unknown Change-Point**:
- We extended the model to consider the change-point k as an unknown parameter, using a discrete uniform prior.
- We then sampled k and analyzed its impact on the posterior distribution of R = θ/λ.
4. **Metropolis Hastings Subsampling**:
- For a more complex analysis, we replaced the third-stage priors with Gamma distributions, removing conjugacy.
- We applied Metropolis Hastings subsampling to β1 and β2 and examined its effect on the posterior distributions for β1, β2, and R = θ/λ.
## Contributions
This project provides insights into the application of Bayesian methods in change-point detection and demonstrates the use of Gibbs sampling and Metropolis Hastings algorithms in parameter estimation. The detailed analysis and results can aid in understanding the historical trends and patterns in coal mining disasters.

# Model Comparison on Regression Models
## Objective
- The objective of this project is to compare two competing regression models, a linear model and a quadratic model, using a given dataset. We aim to determine the marginal distributions for each model and evaluate their performance using the Bayes factor. Additionally, we will explore how the Bayes factor changes when the prior distributions are replaced by improper constant priors.
## Project Overview
- This project involves comparing two competing regression models using a given dataset. Below is a summary of the important questions addressed:
### Question 3.1
- Determine the marginal distributions for a linear regression model.
### Question 3.2
- Determine the marginal distributions for a quadratic regression model.
### Question 3.3
- Calculate the Bayes factor to compare the linear and quadratic models using the given dataset.
### Question 3.4
- Evaluate how the Bayes factor changes when the prior distributions are replaced by improper constant priors.
This overview provides a structured approach to understanding model comparison, giving insights into both linear and quadratic regression techniques.


