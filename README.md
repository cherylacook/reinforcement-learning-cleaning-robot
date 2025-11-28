# Cleaning Robot Reinforcement Learning

This project was *completed as part of AIML232* at Te Herenga Waka — Victoria University of Wellington.

## Objective
Implement policy evaluation, one-step policy improvement, and value iteration for a simple cleaning-robot Markov decision process (MDP) in a deterministic environment. Extend the value iteration process to consider a stochastic environment.

## Structure
- `rl_cleaning_robot.ipynb` - Full implementation and printed results.

## Methods
- Policy Evaluation: Computes the state values under a given deterministic policy π.
- Policy Improvement: Applies one step of the Bellman optimality update.
- Value Iteration: Computes optimal state values for both deterministic and stochastic environments.

## How to Run
```bash
pip install numpy
jupyter notebook
# Open `rl_cleaning_robot.ipynb` and run all cells 
