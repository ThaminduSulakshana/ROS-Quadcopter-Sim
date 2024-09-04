# ROS-Quadcopter-Sim

## Overview
This repository provides a simulation of a quadcopter in ROS (Melodic) using the Gazebo simulator (version 9). The quadcopter model is based on Joop-Brokking's design, with mass and inertia properties identical to the DJI-F450 frame. The simulation uses Approximate Dynamic Programming for stabilization, with plugins for lift generation and motor control.

## Features
- Realistic quadcopter simulation with accurate physics.
- Utilizes ROS Control and Gazebo plugins.
- Based on the DJI-F450 frame for realistic dynamics.

## Prerequisites
- ROS Melodic
- Gazebo 9
- Additional ROS packages:
  ```bash
  sudo apt-get install ros-melodic-gazebo-ros-pkgs ros-melodic-gazebo-ros-control ros-melodic-ros-control ros-melodic-ros-controllers
  sudo apt-get install ros-melodic-joint-state-controller ros-melodic-effort-controllers ros-melodic-position-controllers

## Acknowledgments
Inspired by Joop-Brokking's Quadcopter tutorials. Check out his [YouTube Channel](https://www.youtube.com/channel/UCpJ5uKSLxP84TXQtwiRNm1g) and [Website](http://www.brokking.net/) for more information.


## License

[MIT License](License)