# micro-ros-rp2040
learning micro-ros with Arduino Nano Connect RP2040

## Steps to run :
Make sure all terminals are sourced for```ros2``` and ```micro_ros``` workspace.

1.  Plug the RP2040 Connect and run the micro_ros_agent:

``` ros2 run micro_ros_agent micro_ros_agent serial --dev /dev/ttyACM0```

2. In new terminal view topics :

``` ros2 topic list ```

