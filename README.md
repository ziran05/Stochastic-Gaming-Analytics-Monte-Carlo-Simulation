# Stochastic Gaming Analytics & Monte Carlo Simulation
- Project Overview
This project models a short-memory stochastic process to analyze drop rates, success probabilities, and reward distributions under uncertainty. Instead of relying on static expected values, the framework uses a path-dependent Monte Carlo simulation (1,000 runs) to account for streak-based multipliers and reset mechanics.
# Key Features
- Path-Dependent Stochastic Process: Simulated success/failure trials where consecutive wins generate cumulative score multipliers (+10% per streak step), while any failure resets the streak counter.
- Empirical Monte Carlo Simulation: Generated 1,000 full-run iterations to map the complete empirical probability distribution of final scores.
# Statistical Rigor & Risk Analytics:
- Hypothesis testing using scaled standard errors.
- Goodness-of-fit and distribution bounds across standard confidence intervals 
- Evaluation of tail risks, maximum/minimum yield scenarios, and variance propagation over large trial samples (N = 1,000).
