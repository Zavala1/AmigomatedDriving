# AmigomatedDriving

This repository should contain all files to run a
limited automated driving software on an AmigoBot,
controlled by a RaspberryPi3, using [Ros](ros.org)
with [RosAria](http://wiki.ros.org/ROSARIA).


The RSPi image contains the following pkg: 
ARIA 
SONARNL - library for localizing and navigating mobile robots 
ARVideo - 
ARNL -
MObileSim - for simulation 

The catkin_ws workspace contains the following ROS Nodes
Rosaria 
Rosaria_Client – some examples for the robot interaction using Aria
Sonar_to_laserscan  - to convert the amigobot sonar scan depthcloud data to laserscan data for use by amcl
amr-ros-config – containts a modified xacro for the amigobot and a launchfile with amigobot's state publisher  + rviz + rosaria

Useful links: 
Adding a Raspberry Pi to an AmigoBot Mobile Robot
http://robots.mobilerobots.com/wiki/Adding_a_Raspberry_Pi_to_an_AmigoBot_Mobile_Robot

http://vigir.missouri.edu/~gdesouza/Research/MobileRobotics/Software/ARNL-SONARNL/SonArnl-1.7.0+gcc41/docs/SONARNL-Reference/

http://math.hws.edu/vaughn/cpsc/336/Aria/docs/
