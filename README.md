# UniversalRobot-RealtimeControl
A Fork of https://bitbucket.org/RopeRobotics/ur-interface/src. I reduced the code to the absolute minimum needed for executing commands and added an option for real-time Control of a UR Robot. 

To use the realtime control option, use the functions init_realtime_control() and set_realtime_pose().

init_realtime_control() uploads a program on the robot.

set_realtime_pose() uses standard UR - RTDE communication to send the next pose. 

For a more detailed explanation see the file urScriptExt.py
This code was tested on UR Firmware 3.2
