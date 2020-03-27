# Project4
# Home Service Robot #

The is the final project for the Udacity course Robotics Software Engineer.

## Packages ##
gmapping: With the gmapping_demo.launch file, you can easily perform SLAM and build a map of the environment with a robot equipped with laser range finder sensors or RGB-D cameras.
turtlebot_teleop: With the keyboard_teleop.launch file, you can manually control a robot using keyboard commands.
turtlebot_rviz_launchers: With the view_navigation.launch file, you can load a preconfigured rviz workspace. You’ll save a lot of time by launching this file, because it will automatically load the robot model, trajectories, and map for you.
turtlebot_gazebo: With the turtlebot_world.launch you can deploy a turtlebot in a gazebo environment by linking the world file to it.

## Proejct Setup ##
Python 2.0
Launch from catkin_ws with ./src/scripts/home_service.sh
If I were writing these out as _code_, it might look something like this:
```
if bowl is empty:
    add cereal
if bowl only has cereal in it:
    add milk
```
