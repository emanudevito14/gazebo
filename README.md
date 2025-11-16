Put this repo in ros2_ws/src/iiwa_ros2/iiwa_description. Open new terminal in worlds folder 
```
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:~/ros2_ws/src/iiwa_ros2/iiwa_description/gazebo/models
export GZ_SIM_RESOURCE_PATH=$GZ_SIM_RESOURCE_PATH:~/ros2_ws/src/iiwa_ros2/iiwa_description/gazebo/models
ign gazebo floating_marker.world
```
