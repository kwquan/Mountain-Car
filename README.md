# Mountain-Car
This repo contains the code to solve the mountain car environment using Sarsa with Tiling

# Description
![alt text](https://github.com/kwquan/Mountain-Car/blob/main/mountain_car.png)

In this notebook[MountainCar.ipynb], we shall solve the Mountain Car environment using Sarsa & Tiling. In addition, we shall conduct a parameter study to investigate the effects of different tile/tiling values on timesteps to reach termination 

Aim: The Mountain Car consists of a car placed stochastically at the bottom of a sinusoidal valley, \
     with the only possible actions being the accelerations that can be applied to the car in either direction. \
     The goal of the MDP is to strategically accelerate the car to reach the goal state on top of the right hill. 
     
Observation space: array of shape (2,) comprising of position & velocity of car \
     Action space: 0[UP], 1[RIGHT], 2[DOWN], 3[LEFT] \
          Rewards: \
              1) Each timestep: -1
              
# Documentation
https://www.gymlibrary.ml/environments/classic_control/mountain_car/             
