# Baxter robot ROS-Noetic workspace

Baxter workspace adapted from the original [Rethink Robotics Baxtrer repository](https://github.com/RethinkRobotics/baxter). Compatible with ROS noetic using real robot, with moveit integration using [moveit_robots](https://github.com/ros-planning/moveit_robots) config files.

## Requirements

## Use

```
cd baxter_ws
catkin_make install
```

Copy the baxter.sh file to provide an easy way to configure ROS_MASTER_URI and ROS_IP to connect easily to the robot. 

```
cd baxter_ws
cp src/baxter/baxter.sh
```
