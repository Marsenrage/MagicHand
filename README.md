# Overview

This repository includes the simulation environment for the MagicHand platform, a task-object grasp dataset, and the source code for two reinforcement learning models designed for object manipulation tasks.

<p align="center"> 
<img src="images/PoPdAb2.gif" alt="simu env" width="230"/>
<img src="images/pPdAb23.gif" alt="simu env" width="230"/>
<img src="images/pPdAb24.gif" alt="simu env" width="230" height="156"/>
<img src="images/poPmAb25.gif" alt="simu env" width="230"/>
</p>


# MagicHand
The MagicHand platform is a context-aware dexterous manipulation system comprising a Sawyer robotic arm and an AR10 robotic hand. It integrates multiple sensors, including a RealSense RGB-D camera, a SCiO sensor for near-infrared (NIR) perception, and an inertial measurement unit (IMU).

<p align="center"> 
<img src="images/magichand.jpg" alt="dexDual" width="400"/></p>

The simulation environment is developed using PyBullet within the Gym framework. It supports reinforcement learning and enables a range of applications, including object alignment, pick-and-place, and dexterous manipulation tasks.

# Task-Oriented Objects Dataset
This dataset was revised from the Yale human grasping dataset. It contains human knowledge representation of 6554 grasping tasks.

<p align="center"> 
<img src="images/tood.png" alt="dexDual" width="800"/></p>

