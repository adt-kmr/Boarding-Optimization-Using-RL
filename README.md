# Airplane Boarding Using Reinforcement Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Gymnasium-RL-green?logo=openaigym&logoColor=white" alt="Gymnasium">
  <img src="https://img.shields.io/badge/Stable--Baselines3-RL-orange" alt="Stable-Baselines3">
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557c?logo=matplotlib&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

<img width="1066" height="420" alt="boarding optimization using RL" src="https://github.com/user-attachments/assets/f1dca760-90bb-4cec-8f38-dc6ffde8055d" />


## Overview

This project applies **Reinforcement Learning (RL)** to optimize airplane boarding strategies. The agent learns how to sequence passengers efficiently while minimizing boarding time, aisle congestion, and passenger interference.

## Objectives

- Minimize total boarding time
- Reduce aisle congestion
- Optimize passenger boarding order
- Compare RL with traditional boarding strategies

## Approach

The airplane cabin is modeled as a reinforcement learning environment where the agent observes the current boarding state, selects an action, and receives a reward based on boarding efficiency.

```text
Environment → State → Action → Reward → Agent → Updated Policy
