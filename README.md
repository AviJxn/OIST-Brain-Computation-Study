# OIST Brain Computation Guidebook - Implementations

Python implementations of the mathematical models from the **OIST Brain Computation Guidebook** (Neural Computation Unit).

##  Project Overview
This repository serves as a self-study companion to understand the **computational mechanisms of the brain**, specifically focusing on:
* **Reinforcement Learning (RL):** How the brain learns from reward signals (Dopamine pathways).
* **Scientific Computing:** Implementing algorithms from scratch using Python/Jupyter.

##  Key Experiment: Q-Learning Convergence
In `Reinforcement.ipynb`, I replicated the standard Q-learning agent on the Pain-Gain environment.
* **Hypothesis:** The default learning rate **(α = 0.1)** resulted in slow initial convergence.
* **Modification:** I increased the learning rate to **(α = 0.5)** to prioritize recent reward signals.
* **Result:** The agent demonstrated significantly faster policy acquisition in the early training phase (visible in the final learning curve plot).

##  Contents
* `Reinforcement.ipynb`: Implementation of value iteration, policy iteration, and dopamine-based reward prediction error models.

##  Why this matters
As an aspiring contributor to **INCF**, I believe it is critical to understand not just the *infrastructure* (RAG, Search), but also the *science* (Neuroinformatics) that the infrastructure supports.
