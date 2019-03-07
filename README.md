husky
=====

Common ROS packages for the Clearpath Husky, useable for both simulation and
real robot operation.

 - husky_control : Control configuration
 - husky_description : Robot description (URDF)
 - husky_msgs : Message definitions
 - husky_navigation : Navigation configurations and demos

For Husky instructions and tutorials, please see [Robots/Husky](http://wiki.ros.org/Robots/Husky).

To create a custom Husky description or simulation, please fork [husky_customization](https://github.com/husky/husky_customization).

husky_desktop
=============

Desktop ROS packages for the Clearpath Husky, which may pull in graphical dependencies.

 - husky_viz : Visualization (rviz) configuration and bringup

For Husky instructions and tutorials, please see http://wiki.ros.org/Robots/Husky

husky_robot
===========

Robot ROS packages for the Clearpath Husky, for operating robot hardware.

 - husky_bringup : Bringup launch files and scripts.
 - husky_base : Hardware driver for communicating with the onboard MCU.

For Husky instructions and tutorials, please see http://wiki.ros.org/Robots/Husky

husky_simulator
==============

Simulator ROS packages for the Clearpath Husky.

 - husky_gazebo : Gazebo plugin definitions and extensions to the robot URDF.

For Husky instructions and tutorials, please see http://wiki.ros.org/Robots/Husky

ROS Melodic installation tips
==============
To build husky on melodic, you need to install these things using apt:
 - ros-melodic-robot-localization
 - ros-melodic-twist-mux
You also need these two things that are not in the apt repository, clone the repos in your workspace, they should build as is:
 - https://github.com/ros-visualization/interactive_marker_twist_server
 - https://github.com/clearpathrobotics/LMS1xx


