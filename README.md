# Lunar Lander Deep Q-Network (DQN) Agent using Stable Baselines3

This repository implements a Deep Q-Network (DQN) agent using the stable-baselines3 library to solve the Lunar Lander environment from OpenAI Gymnasium. The DQN agent learns to navigate and land a spacecraft safely on the moon's surface through reinforcement learning.

## Contributors

- Royston Rex Fernandez 
- Asher Anil Kurian
- Atshaya Srinivasan 
- Herman Basajjabalaba

## Description

The DQN agent is trained to solve the Lunar Lander environment provided by OpenAI Gymnasium. The agent utilizes a deep neural network architecture to approximate the Q-function, enabling it to make decisions based on the observed state of the environment.

## Features

- Implementation of the Deep Q-Network (DQN) algorithm
- Utilizes stable-baselines3 library for reinforcement learning
- Training over 500,000 timesteps
- Evaluation over 1000 episodes
- Plotting of training loss and rewards
- Saving of trained model and evaluation video

## Requirements

- Python 3.7+
- gym
- numpy
- matplotlib
- cv2
- pandas
- stable-baselines3

You can install the required libraries using pip:

```bash
pip install gym numpy matplotlib opencv-python pandas stable-baselines3
