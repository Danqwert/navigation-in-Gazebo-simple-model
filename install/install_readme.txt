# Dependences (ROS Noetic required)
sudo apt install ros-noetic-gmapping ros-noetic-ros-control ros-noetic-ros-controllers ros-noetic-navigation ros-noetic-robot-localization

# Build package
cd ~/catkin_ws/
make -j4 -l4

# Run
roslaunch robot robot_gazebo_map.launch
roslaunch robot robot_nav_map.launch