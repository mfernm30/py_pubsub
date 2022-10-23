# py_pubsub

This is a simple ROS2 publisher and subscriber nodes written in Python.

## Install dependencies
```
rosdep install --from-paths src --ignore-src -r -y
```

## Build package
Located at dev_ws
```
colcon build
```

## Source enviroment
Located at dev_ws
```
source install/setup.bash
```

## Usage
Run publisher node
```
ros2 run py_pubsub publisher
```
Run subscriber node
```
ros2 run py_pubsub listener
```