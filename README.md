# Running-Cartographer-Localisation-on-Turtlebot

This repository contains the necessary files to run robots using Cartographer for localization. Ensure that Google's Cartographer libraries are installed before proceeding.

## Setup

### Fork
1. Click fork on the top right.
2. Select namespace, choose your username.
3. Select Visibility to Private.
4. Click Fork Project.

### Clone Repo to Local Machine
1. Copy the clone with the HTTPS link.
2. Open a terminal in Ubuntu.
3. Using the terminal, navigate to a folder where you want to save the homeworks.
4. Install Git, Clone repo, set upstream.

After cloning the repo, run the following commands on a laptop with Ubuntu 20.04 and ROS Noetic:
```bash
roslaunch turtlebot_gazebo turtlebot3_house.launch
roslaunch turtlebot_navigation turtlebot3_navigation_carto.launch
roslaunch turtlebot_bringup turtlebot3_remote_turtle_gazebo_nopb.launch


