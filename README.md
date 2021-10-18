# Scorbot_ER_servoing

```
cd
cd .gazebo/models/
cp -r /home/user/catkin_ws/src/scorbot_er/marker0 .
```
safdaf

```
roslaunch scorbot_er_description servoing.launch
roslaunch scorbot_er_description artag.launch
rostopic echo -n 1 /ar_pose_marker
```
