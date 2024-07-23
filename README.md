# Clearpath-Jackal
SIT18-Jackal-robot clearpath jackal robot deploys on board laser

# Installation:
Install Ubuntu and ROS (Tested on Ubuntu 20.04 and ROS Noetic)

`sudo apt install ros-noetic-jackal-simulator`

`sudo apt install ros-noetic-jackal-desktop`

# Launch Gazebo Simulation:

`roslaunch jackal_gazebo jackal_world.launch config:=front_laser`

![](https://github.com/SunnyGuang/Clearpath-Jackal/blob/main/jackal_msgs/gazebo-jackal-race.png)

# Launch Rviz:

`roslaunch jackal_viz view_robot.launch`
