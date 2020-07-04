# TurtleBot-simulation-ROS-kinetic-
## The video link for running the Turtlebot simulation 
##### https://www.youtube.com/watch?v=rP4cf7dahKc
#### First thing is running the master. 
###### roscore
#### Then running the gazebo world with the turtlebot.
###### roslaunch turtlebot_gazebo turtlebot_world.launch
#### Running Rviz for capturing sensor information from Turtlebot sensors.
###### roslaunch turtlebot_rviz_launchers view_robot.launch
#### The last thing running the keyboard controller to move the Turtlebot.
###### roslaunch turtlebot_teleop keyboard_teleop.launch



