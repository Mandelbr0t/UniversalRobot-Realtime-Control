# UniversalRobot-RealtimeControl
A Fork of https://bitbucket.org/RopeRobotics/ur-interface/src. I reduced the code to a minimum needed for executing commands and added an option for real-time Control of a UR Robot. 

To use the realtime control option, use the functions init_realtime_control() and set_realtime_pose().

init_realtime_control() uploads a program on the robot.

set_realtime_pose() uses standard UR - RTDE communication to send the next pose. 

For a more detailed explanation see the file urScriptExt.py.

This code was tested on UR5 Firmware 3.2 and utilized in the reinforcement learning code for the paper `Bézier Curve Based Continuous and Smooth Motion Planning for Self-Learning Industrial Robots`
