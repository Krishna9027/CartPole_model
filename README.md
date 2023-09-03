# CartPole_model

# INTRODUCTION_
The CartPole problem is a classic reinforcement learning task where the goal is to balance a pole on a moving cart for as long as possible. In this project, we use the Actor-Critic method to train an agent that learns to control the cart and pole to achieve this objective.

# Prerequisites
Before you begin, ensure you have met the following requirements:

1.Python 3.6+

2.gym library: Install it using pip install gym


# Set Up
Import necessary packages and configure global settings

1.pip install gym[classic_control]
2.pip install pyglet

# Installation 
1.Clone this repository to your local machine:
    
      git clone https://github.com/yourusername/cartpole-actor-critic.git

2.Navigate to the project directory:
  cd cartpole-actor-critic

# Usage
You can use the trained agent to play CartPole or train it from scratch.

# Playing with a Pretrained Agent
To play CartPole using a pretrained agent, run the following command:

    python play_cartpole.py --model_path models/pretrained_actor_critic_model.pth

# Training
To train the Actor-Critic agent from scratch, use the following command:

    python train_actor_critic.py

# Contributing
Contributions are welcome! If you find any issues or want to enhance the project, feel free to open a pull request.
