记录数据运行的launch文件
1、roslaunch prometheus_gazebo sitl_pos_control_ude.launch----->普通pid(需修改圆的参数，在terminal_control.yaml修改，相对与下面两个半径需要增加，速度需要降低)
2、roslaunch prometheus_gazebo sitl_pos_control_casecade_pid.launch------串级pid
3、roslaunch prometheus_gazebo sitl_pos_control_ne.launch------>tanh+智能pid（别打开gazebo，影响性能）
