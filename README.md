# Reinforcement Learning Labs

This repository contains practical labs and example implementations for various reinforcement learning (RL) algorithms. The structure is organized by algorithm type, with each folder containing Jupyter notebooks and resources for hands-on experimentation.

## Directory Structure

- **DQL/**

  - Deep Q-Learning (DQN) and Double DQN implementations and experiments.
  - Notebooks:
    - `Double_DQN.ipynb`: Double DQN implementation.
    - `DQN_agent_not_use_replay_experience .ipynb`: DQN without experience replay.
    - `DQN_trained_on_correlated_experiences.ipynb`: DQN trained on correlated experiences.
    - `EX1_DQN_CartPole_2026.ipynb`: DQN on CartPole environment.
    - `Solution_DQN_CartPole_2026.ipynb`: Solution notebook for DQN CartPole.
    - `checkpoint.pth`: Model checkpoint file.

- **Q_learning/**

  - Classical Q-Learning and SARSA algorithm examples.
  - Notebooks:
    - `EX1_randomAgent.ipynb`: Random agent baseline.
    - `Ex2_Q_Learning.ipynb`: Q-Learning implementation.
    - `EX3_SARSA.ipynb`: SARSA algorithm implementation.

- **reinforce_algorithm/**
  - Policy gradient methods using the REINFORCE algorithm.
  - Notebooks:
    - `EX1_REINFORCE_Policy_Gradient.ipynb`: REINFORCE policy gradient example.

## Getting Started

1. **Requirements**: Install Python 3.x and Jupyter Notebook.
2. **Dependencies**: Most notebooks use standard RL libraries such as `gym`, `numpy`, and `torch`. Install them with:
   ```bash
   pip install gym numpy torch
   ```
3. **Usage**: Open any notebook in Jupyter and run the cells to experiment with different RL algorithms.

## Purpose

These labs are designed for educational purposes, to help you understand and experiment with core RL algorithms, including:

- Deep Q-Learning (DQN)
- Double DQN
- Q-Learning
- SARSA
- REINFORCE (Policy Gradient)

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

