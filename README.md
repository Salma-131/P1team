# P1team

## Autonomous Racing Car Simulation

This project simulates a small Formula 1-style car navigating a virtual track using **ROS 2** and **Gazebo**. The car follows predefined waypoints to drive autonomously, without relying on sensors.  

### Key Features
- Python-based ROS 2 nodes for control  
- Waypoint navigation for self-driving behavior  
- Speed adjustments for curves to maintain stability  
- Runs in **Gazebo 11** on Windows via WSL + Ubuntu 22.04  

### How It Works
The car calculates its position relative to the next waypoint at each simulation step and adjusts its steering and speed accordingly. Sharp turns trigger automatic speed reduction to keep control.  

### Technology Stack
- ROS 2 Humble Hawksbill  
- Gazebo 11  
- Python 3  
- Ubuntu 22.04 (via WSL)  
- Windows 10/11  

### Future Improvements
- Add sensors like LIDAR or camera for environment perception  
- Implement PID control for smoother motion  
- Include advanced path planning algorithms (A*, RRT)  
- Real-time obstacle detection and avoidance  

### Academic Note
This repository contains my independent version of a team project for academic submission.
