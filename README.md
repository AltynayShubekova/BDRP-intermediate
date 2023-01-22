# BDRP-intermediate
This repository contains intermediate results of our Big Data Research Project on 3D Bin Packing with Deep Reinforcement Learning.

In the attached notebook we use the Jumanji environment to train a reinforcement learning agent to solve 3D Bin Packing Problem. The agent is trained using the DQN algorithm. The script creates a replay buffer and neural network, and uses them to train the agent. It also includes a function to flatten the observation data from the environment. 

At the very end of the file, the script throws an error, it is due to the fact that in this part of the code we run an endless loop in which items are added to the box. The error comes out because we end running.

Here's a demo of the best items stacking we've achieved so far:

![Запись_экрана_22_01_2023_3_00_13_online_video_cutter_com](https://user-images.githubusercontent.com/122653127/213897391-693b783b-e9cc-4c4b-9ebc-6df1a3e115c5.gif)
