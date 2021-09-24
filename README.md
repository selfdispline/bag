roslaunch prometheus_gazebo sitl_pos_control_ne.launch# bag
记录数据运行的launch文件
1、roslaunch prometheus_gazebo sitl_control.launch----->普通pid
2、roslaunch prometheus_gazebo sitl_pos_control.launch------串级pid
3、roslaunch prometheus_gazebo sitl_pos_control_ne.launch------>tanh+智能pid
