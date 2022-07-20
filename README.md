# Mountain-Car
This repo contains the code to solve the mountain car environment using Sarsa with Tiling

# Description
![alt text](https://github.com/kwquan/Mountain-Car/blob/main/mountain_car.png)

In this notebook[MountainCar.ipynb], we shall solve the Mountain Car environment using Sarsa & Tiling. In addition, we shall conduct a paramter study to investigate the effects of different tile/tiling values on timesteps to reach termination \
Aim: The Mountain Car consists of a car placed stochastically at the bottom of a sinusoidal valley, \
     with the only possible actions being the accelerations that can be applied to the car in either direction. \
     The goal of the MDP is to strategically accelerate the car to reach the goal state on top of the right hill. 
Gridspace: 4x12 \
Action space: 0[LEFT], 1[NOTHING], 2[RIGHT] \
Rewards:
1) Each timestep: -1
