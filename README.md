# Deep Q-Learning Convolutional Pac-Man Agent 🕹️👾

This project implements a **Deep Q-Learning** agent using a **Convolutional Neural Network (CNN)** to play the classic **Pac-Man** game.  
The agent learns how to navigate the environment, avoid ghosts, and collect pellets by interacting with the game environment and improving its policy over time.

---

## 🎯 Project Overview

Deep Q-Learning (DQN) combines **Q-Learning** with **Deep Neural Networks** to handle high-dimensional state spaces.  
In this project, the state is represented as **preprocessed frames** from the Pac-Man game, and the agent learns by trial and error through **experience replay** and **target networks**.

The main components:
- **Game Environment**: Pac-Man environment (Gym-compatible or custom).
- **Agent**: A CNN-based DQN model to predict the Q-values for possible actions.
- **Training Loop**: Agent plays episodes, stores experiences, and updates its policy.
- **Evaluation**: Tracks score, survival time, and loss over episodes.

---

## 🧠 Features

- **Convolutional Neural Network (CNN)** for processing visual game frames.
- **Experience Replay** buffer to stabilize learning.
- **Target Network** to reduce Q-value oscillations.
- **Frame Stacking** for motion awareness.
- **Epsilon-Greedy Policy** for exploration vs exploitation.
- **Reward Shaping** to encourage pellet collection and survival.

---
