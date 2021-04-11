# ROS_Drone
My ROS project #e-yantra

Using ROS(Robot Operating System) and simulating software Gazebo, build an drone-based waypoint navigation project.
**Description:**
Here is the simplest implementation of multi-point waypoint tracking using PID controlled algorithm for drone.
Drone runs on the principle of PID controller to adjust its pitch, yaw and thrust values to travel around.
There is a whycon marker which is mounted on top of the drone, with the help of it camera plug-in inside gazebo locates the position of drone. 

**Software Used**
1. ROS-kinetic
2. Gazebo 7
3. OS - ubuntu xenial(14.0.4)
4. Python 2.7

**HOW TO RUN**
1. Setup ROS2(kinetic) and Gazebo7 environment in your desktop
2. Dowload or clone this repository to your local machine

*Multi-point navigation*
-Open a terminal write command -**roscore**
-Open a different terminal window ender -**roslaunch survey_and_rescue launch_gazebo_and_whycon.launch**
-Open a different terminal window ender -**rosrun survey_and_rescue position_hold_gazebo.py**


**single-waypoint travelling** youtube link - *https://www.youtube.com/watch?v=THdr92HtibA*
**Multi-waypoint travelling** youtube link - *https://www.youtube.com/watch?v=voFd28q17pU*
