# Clearpath-Jackal
SIT18-Jackal-robot clearpath jackal robot deploys on board laser

# Installation:
Install Ubuntu and ROS (Tested on Ubuntu 20.04 and ROS Noetic)

`sudo apt install ros-noetic-jackal-simulator`

`sudo apt install ros-noetic-jackal-desktop`

`sudo apt-get install ros-noetic-sick-tim`

`sudo apt-get install ros-noetic-flir-camera-description`

# Launch Gazebo Simulation:

`roslaunch jackal_gazebo jackal_world.launch config:=front_laser`

![](https://github.com/SunnyGuang/Clearpath-Jackal/blob/main/jackal_msgs/gazebo-jackal-race.png)

# Launch Rviz:

`roslaunch jackal_viz view_robot.launch`

![](https://github.com/SunnyGuang/Clearpath-Jackal/blob/main/jackal_msgs/rviz-jackal-laser.png)

# Launch Mapping:
Using gammping for mapping:

`roslaunch jackal_navigation gmapping_demo.launch`

To visualize during mapping:

`roslaunch jackal_viz view_robot.launch config:=gmapping`

# Launch Navigation:
Navigation demo:

`roslaunch jackal_navigation odom_navigation_demo.launch`

Rviz:

`roslaunch jackal_viz view_robot.launch config:=navigation`

Project is still updating, if you have any questions, please feel free to leave your question in "Issue".
