# ROS UR10 Manipulator Control

Real-time trajectory control and inverse kinematics for UR10 robot in Gazebo simulation using ROS2 and MATLAB.

## Features
- **Inverse Kinematics**: IK solver for UR10 end-effector pose control
- **Real-time Monitoring**: 50 Hz joint state acquisition via ROS subscribers
- **Trajectory Execution**: Point-to-point and multi-waypoint motion with velocity profiles
- **Data Acquisition**: Time-stamped recording of joint positions and velocities
- **Visualization**: Joint state and velocity plots for motion analysis

## Technologies
- ROS, Gazebo, MATLAB Robotics Toolbox
- UR10 URDF model, Inverse Kinematics Solver
- TCP communication, Action Client/Server interfaces

## Key Results
- Quintic trajectory execution with smooth velocity profiles
- Real-time joint state monitoring and visualization
- Motion accuracy validated through commanded vs. actual joint tracking

## Project Structure
- `ROS_Final.mlx`: Main trajectory control script
- Inverse kinematics solver setup
- Multi-waypoint trajectory planning and execution
- Statistical motion analysis and plotting
