# Formation Control of Multiple Swarm Robots
The objective of this project is to control multiple Spark V robots simultaneously to form any desired shapes. The shapes can be predefined: like the shapes of letters, or can be drawn on the screen. 

We used an overhead camera for obtaining the position of the robots. The robots are controlled using a python script running on a laptop.
OpenCV libraries are used along with python for the detection of ArUco markers which are placed the robots using which we obtain the 
position and orientation each robot.

XBee radio modules are used for the communication between the laptop and the robots.
The laptop sends the robot's position and orientation to the robot along with its 
desired position. The robot then moves towards the required position using a Go-to-Goal PID controller running on the robot.

Thus multiple robots are directed to the required positions to form a desired shape.

This repository contains the Python Image Procssing scripts, embedded C codes for the Spark V robot and all the documentation of the project.

## Video Demonstration
[Robots forming various shapes](https://youtu.be/5OJM3ENlbsU)

[Robots forming the word "eYANTRA"](https://youtu.be/7awbPJ00wAU)
