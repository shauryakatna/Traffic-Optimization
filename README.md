<h1 align="center"> Traffic Light Optimization With Reinforcement Learning </h1>

This project offers a framework for optimizing traffic flow at complex intersections using a Deep Q-Learning Reinforcement Learning agent. By intelligently selecting traffic light phases, the agent aims to maximize traffic efficiency.

## Deep Q-Learning Agent

- **Framework**: Q-Learning with a deep neural network.
- **Context**: Traffic signal control at a single intersection.
- **Environment**: Features a 4-way intersection with 4 incoming and outgoing lanes per arm, each 750 meters long. Traffic lights are positioned such that each arm has dedicated lanes for specific movements.
- **Traffic Generation**: Each episode generates 1000 cars following a dynamic pattern, contributing to the complexity of the environment.
- **Agent (Traffic Signal Control System - TLCS)**:
  - **State**: Discretized representation of oncoming lanes, identifying vehicle presence in cells.
  - **Action**: Selection of traffic light phases from predetermined options, each lasting 10 seconds.
  - **Reward**: Based on cumulative waiting time reduction, incentivizing efficient traffic management.
  - **Learning Mechanism**: Utilizes Q-learning equation and a deep neural network to update action values and learn state-action relationships.


