# Path-planning-and-control-for-Turtlebot

Program to drive a Turtle-bot (Differential drive robot) in a polygon shape of user-defined length and number of sides.

The program computes a path for given number of sides and provides waypoints for each corresponding vertex. To ensure path is followed, proportional control is used.

To run the program:

1. Place zip file in catkin_ws/src. and unzip

2. Start roscore; make and source the workstattion using 'catkin_make' and '. devel/setup.bash' on 2 other terminals.

3. On a seperate terminal, launch gazebo using 'roslaunch assignment_2 assignment_2_world.launch' for simulation.

4. On a seperate terminal, run the main python code using 'python prop_polygon.py'

Implemented on Turtlebot(Video): https://youtu.be/fpV0yEskQFI
