# DRL-Banana-Unity


## Project Details

This is the first project of the Udacity Deep Reinforcement Learning nanodegree. The objective is to collect yellow bananas and avoid blue ones by moving in the virtual environment. A reward of +1 is given for collecting a yellow banana and a reward of -1 for collecting a blue one. These are the details of this Unity environment:

```
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 
```

States have 37 features containing the agent's velocity and ray-based perception of objects agent's forward direction. There are four possible actions:
 
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.


## Getting Started

You will need to download the Unity environment from one of these links depending on your operating system:

- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

The code is written in Python. Make sure you have a  `python 3.6` environment with the following dependencies: `PyTorch` and `ml-agents`

## Instructions

Run the notebook `Solution.ipynb` to train an agent.

