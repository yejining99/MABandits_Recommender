# Multi-Armed Bandits
## Linear Upper Confidence Bound (LinUCB) and Thompson Sampling (TS)

This repository contains the code for implementing the Linear Upper Confidence Bound (LinUCB) and Thompson Sampling (TS) algorithms for multi-armed bandit problems.

## ☑️ Linear Upper Confidence Bound (LinUCB)

LinUCB is an algorithm for solving the multi-armed bandit problem, where the goal is to find the best arm to pull given a set of arms, each with their own unknown reward distribution. LinUCB uses a linear model to estimate the reward for each arm, and chooses the arm with the highest upper confidence bound.

## ☑️ Thompson Sampling (TS)

TS is a Bayesian algorithm for solving the multi-armed bandit problem. It samples from the posterior distribution of the rewards for each arm, and chooses the arm with the highest sample.


## References

LinUCB: "LinUCB: A Contextual Bandit Algorithm with Linear Payoffs"
TS: "A Tutorial on Thompson Sampling"

Note) This implementation is for educational purpose and it is not optimized for performance.
