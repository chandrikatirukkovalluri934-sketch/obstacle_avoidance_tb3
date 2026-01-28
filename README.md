# Reactive Obstacle Avoidance for TurtleBot3 (ROS 2)

## Overview

This project presents the design and implementation of a reactive obstacle avoidance system for a TurtleBot3 mobile robot using ROS 2 Humble. The robot navigates autonomously in a Gazebo simulation environment using only data from a 360-degree LIDAR sensor, without relying on mapping, localization, or global path planning.

Based on obstacle proximity, the robot dynamically decides whether to move forward, rotate, or stop, enabling safe and collision-free navigation in unknown environments. The system is lightweight, computationally efficient, and suitable for real-time operation.

This project was developed as part of the Robot Operating Systems coursework.

---

## Key Features

- Reactive obstacle avoidance using only LIDAR data  
- No SLAM, no mapping, no global planner  
- Real-time decision making  
- Gazebo-based simulation  
- ROS 2 Humble compatible  
- Portable and reproducible execution  

---

## System Requirements

### Software
- Ubuntu 22.04  
- ROS 2 Humble  
- Python 3  
- Gazebo Simulator  
- Docker (optional)

### Hardware (Simulated)
- TurtleBot3 Waffle Pi  
- 360° LIDAR sensor  

---

## Approach 1: Docker-Based Execution

1. Build Docker image:
```bash
docker build . -t turtlebot3_container
---

## Author

Chandrika Tirukkovalluri  
Matriculation Number: 12502910  
Technische Hochschule Deggendorf – Campus Cham  

---
