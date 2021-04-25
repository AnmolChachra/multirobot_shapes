# multirobot_shapes
The robots coordinate to get to specific locations. One robot will be the leader and the other robots will be the follower. For example, if 3 robots are in the world, they will coordinate with each other to arrange themselves on the vertices of a triangle. Number of robots = Number of wapoints. See ProblemDescription.pdf for more details

## Requirements
<ul><li>ROS -- tested on Melodic, but other versions may work
  </li><li>catkin_make -- used for building the application</li><li>turtlebot3_description -- https://github.com/AnmolChachra/turtlebot3_description (clone this in your src dir)</li></ul>

## Build
Once cloned in a ROS workspace, e.g. `/root/catkin/`, run the following commands to build it:
```
catkin_make
source devel/setup.bash
```

### Run for gazebo
```
roslaunch multirobot_shapes multirobot_shapes_gazebo.launch
```
