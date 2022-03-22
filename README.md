# py_pubsub

This is a simple ROS2 publisher subscriber written in Python.

## Intall ependencies

rosdep install --from-paths src --ignore-src -r -y

# Build package

Located at dev_ws
colcon build

# Source enviroment

Located at dev_ws
source install/setup.bash

## Usage

ros2 run py_pubsub publisher
ros2 run py_pubsub listener