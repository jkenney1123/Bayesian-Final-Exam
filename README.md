# Bayesian Data Analysis Final Exam

For the deployed html website use the following link
https://jkenney1123.github.io/Bayesian-Final-Exam/

# Project Overview
This project focuses on the comparison of two statistical models using Bayesian methodology. Specifically, the Bayes Factor is employed to determine which model better fits the given data. The analysis involves integrating out parameters using improper constant priors and evaluating the marginal distributions.


## Key Components
1. **Bayes Factor Calculation**:
- The Bayes Factor is used to compare two models by evaluating the ratio of their marginal likelihoods.
- This project calculates the Bayes Factor for comparing Model 1 and Model 2, showing dependency on constants \(c1\) and \(c2\).
2. **Integration and Marginal Distributions**:
- Parameters \(β1\), \(β2\), \(γ1\), \(γ2\), and \(γ3\) are integrated out to obtain the marginal distributions.
- The project derives the necessary formulas to perform these integrations.
3. **Model Evaluation**:
- The Bayes Factor is evaluated for a given dataset, indicating that Model 1 (\(H1\)) may be a better fit with a calculated Bayes Factor of 0.42017.
## Additional Components
4. **Prior Choice Project**:
- This component explores the impact of different prior choices on the model's performance.
- It includes a detailed analysis of how the selection of priors affects the Bayes Factor and overall model comparison.
5. **Change Point Model with Different Prior Choices**:
- This part of the project involves applying Bayesian change point models with various prior choices.
- It examines how the choice of priors influences the detection and estimation of change points in the data.
6. **Convergence Diagnostics**:
- Convergence diagnostics are performed to ensure the reliability of the Bayesian inference.
- The project employs various diagnostic tools to check the convergence of the Markov Chain Monte Carlo (MCMC) simulations used in the analysis.
## Results
The final results demonstrate that the Bayes Factor supports Model 1 over Model 2 for the given dataset. This conclusion is based on comprehensive mathematical derivations and integrations presented in the project. Additionally, the prior choice project and the change point model analysis provide further insights into the robustness and sensitivity of the Bayesian models to prior selections.
## Usage
To replicate the analysis, please refer to the code provided in the repository. The implementation details and necessary functions are documented within the codebase for ease of understanding and replication.
---
This summary provides a clear overview of the Bayesian Model Comparison project, focusing on the key components, additional analyses, and results, and is intended for the GitHub README to introduce and explain the project to users.
