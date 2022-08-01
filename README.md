# ros-tf2_dynamic
ROS TF2 publisher with dynamic reconfiguration for manual tf settings

1.catkin_make

2.rosparam set use_sim_time true

3.rosrun rqt_reconfigure rqt_reconfigure

4.rosbag play a.bag, and visualize tf

## before

![](image/before.png)


## after

![](image/after.png)
