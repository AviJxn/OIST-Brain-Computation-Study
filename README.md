# OIST Brain Computation Guidebook - Implementations

Python implementations of the mathematical models from the **OIST Brain Computation Guidebook** (Neural Computation Unit).

##  Project Overview
This repository serves as a self-study companion to understand the **computational mechanisms of the brain**, specifically focusing on:
* **Reinforcement Learning (RL):** How the brain learns from reward signals (Dopamine pathways).
* **Scientific Computing:** Implementing algorithms directly from mathematical models using Python.

##  Key Experiment: Hyperparameter Sensitivity
In `Reinforcement.ipynb`, I implemented the Q-learning agent on the 'Pain-Gain' MDP.
* **Hypothesis:** The default learning rate (α=0.1) resulted in slow convergence.
* **Modification:** I performed a sensitivity analysis by increasing the learning rate to **α=0.5**.
* **Result:** The agent demonstrated significantly faster policy acquisition (reduced time-to-convergence), confirming that higher learning rates prioritize recent rewards in deterministic environments.

##  Contents
* `Reinforcement.ipynb`: Implementation of value iteration, policy iteration, and dopamine-based reward prediction error models.

##  Why this matters
As an aspiring contributor to **INCF**, I believe it is critical to understand not just the *infrastructure* (RAG, Search), but also the *science* (Neuroinformatics) that the infrastructure supports.
