# Obstacle Avoidance Robot Simulation  

## Prerequisites  

* [ROS](http://wiki.ros.org/melodic)  
* [Gazebo](http://wiki.ros.org/gazebo_ros_pkgs)

## Getting Started


1. Run `catkin_make` for both `catkin_ws` and `simulation_ws`.
2. Launch your terminal and run the command `roslaunch my_worlds <world_name>.launch`. 
This will launch the gazebo enviroment
3. In another terminal, run the command `roslaunch robot_description spawn.launch`. 
This will load the robot in the environment at origin. It can be spawned at different location by giving additional arguments like `x:=3 y:=8 z:=7`.  
4. In another terminal run `rosrun motion_plan obstacle_avoidance.py`. This will start the robot and obstacle avoidance algorithm.

