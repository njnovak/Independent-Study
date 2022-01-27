# Independent Study Project

This package is used to run a modified version of the fetch gazebo package. In this package the robot will pick and place two cubes to stack them on top of one another.

Of note, stacking may require a few different runs as the robots recovery behavior can occur when it should not and prevent it from arriving at the right pose.

# Instructions:

To run this package, first put it inside of a workspace, and change directory into indep_ws.

Next, run $ catkin build  and then run $ source devel/setup.bash

Then, run $ roslaunch fetch_gazebo playground.launch

Next, after it loads up, run $ roslaunch fetch_gazebo_demo demo.launch

Sit back and watch the operation!
