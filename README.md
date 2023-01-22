# BDRP-intermediate
This repository contains intermediate results of our Big Data Research Project on 3D Bin Packing with Deep Reinforcement Learning.

In the attached notebook we use the Jumanji environment to train a reinforcement learning agent to solve 3D Bin Packing Problem. The agent is trained using the DQN algorithm. The script creates a replay buffer and neural network, and uses them to train the agent. It also includes a function to flatten the observation data from the environment. 

At the very end of the file, the script throws an error, it is due to the fact that in this part of the code we run an endless loop in which items are added to the box. The error comes out because we end running.

Here's a demo of the best items stacking we've achieved so far:
