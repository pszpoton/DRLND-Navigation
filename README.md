# Solution - Project 1: Navigation

### Introduction

This is a solution for Udacity Deep Reinforcement learning course to train an agent to navigate and collect yellow bananas in a large 3D scene. The project contains the code to train and evaluate the agent to score at least 13 points on average over 100 consecutive episodes. It contains the following files:

-Navigation.ipynb which is a jupyter notebook file that intiate the environment and the agent run training and evaluation
-agent.py which implements Deep Q Reinforcement Learning algorithm with experience relay and fixed Q-Target
-model.py that provide the structure of two identical linear Neural Networks used inside the agent


A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.


### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Follow the instruction to install [DRLND repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)
3. Run cells in Navigation.ipynb that coresponds to any action of choice:
- To train the agent run everything what is under Initiate the agent and start training header
- To evaluate previousely saved agent run everything that is under evaluate agent header
