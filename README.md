Put this repo in ros2_ws/src/iiwa_ros2/iiwa_description
```
git clone https://github.com/emanudevito14/gazebo.git
```
Open new terminal in ros2_ws/src/iiwa_ros2/iiwa_description/gazebo/worlds
```
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:~/ros2_ws/src/iiwa_ros2/iiwa_description/gazebo/models
export GZ_SIM_RESOURCE_PATH=$GZ_SIM_RESOURCE_PATH:~/ros2_ws/src/iiwa_ros2/iiwa_description/gazebo/models
ign gazebo floating_marker.world
```
