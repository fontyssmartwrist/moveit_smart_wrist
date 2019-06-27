
MoveIt! Smart Wrist Package
=====================================================================

This package is used for fk, ik and pathplanning for the Fontys Smart Wrist.

Dependencies
=====================================================================
[The robot model](https://github.com/fontyssmartwrist/sw_v3_description)

[MoveIt! commander ROS node](https://github.com/fontyssmartwrist/smart_movement)

Install guide
=====================================================================
   1) Install MoveIt! kinetic with the following command

	sudo apt install ros-kinetic-moveit

   2) Install MoveIt! TRAC-IK plugin with the following command

	sudo apt-get install ros-kinetic-trac-ik-kinematics-plugin

   3) Clone this project and the dependencies to your catkin's workspace src folder
   4) Run catkin_make to build 
   
Documentation
=====================================================================
Documentation how it works can be found in the [wiki](https://github.com/fontyssmartwrist/smart_movement/wiki).

Authors
=====================================================================
Aike van Alkemade 

