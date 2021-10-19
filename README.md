# Scorbot_ER_servoing

This package contain the implementation of the visual servoing for the Scorbot-ER. For setup the enviroment you have to write this line of code in the terminal: 

```
cd
cd .gazebo/models/
cp -r /home/user/catkin_ws/src/scorbot_er_servoing/marker0 .
```



```
roslaunch scorbot_er_gazebo servoing.launch
roslaunch scorbot_er_gazebo artag.launch
rostopic echo -n 1 /ar_pose_marker
```
