# deep_reinforcement_learning_project1
## Overview
This project trains an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.

1 - move backward.

2 - turn left.

3 - turn right.

The task is episodic, my agent get an score of +15 over 100 consecutive episodes which is larger than +13 which the project requires.

## Getting Started

### Download the Unity Environment
For this project, you will not need to install Unity if you work on udacity - this is because udacity have already built the environment for you

## Code Architecture
Navigation.ipynb: jupyter notebook based solution

dqn_agent.py: DQN agent code

model.py: Q-Network based model

checkpoint.pth: weights of the DQN model

## Instructions

## Result

![image](https://user-images.githubusercontent.com/109795677/188405300-c6f23ae7-21cc-48b8-9fb9-976e4d2027bf.png)
