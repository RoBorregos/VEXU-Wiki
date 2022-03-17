# VEXU-wiki

Welcome to the VEXU-Wiki repository! This is the repository of the RoBorregos Robotics Team for the VEX U 2022 competition. The main purpose of this repository is to documentate and demonstrate the work done during the competition period.
[Wiki](https://github.com/RoBorregos/VEXU-Wiki/wiki)


## Area Setup
0. Development [Setup](https://github.com/RoBorregos/Robocup-Home/wiki/Docker-Usage) using Docker with Ros-Melodic
1. Ubuntu 18 Operative System [installation](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit) on Jetson Nano
2. Dependencies installation ([PROS](https://pros.cs.purdue.edu/v5/getting-started/linux.html), [ROS-Melodic](http://wiki.ros.org/melodic/Installation/Ubuntu), [Tensorflow 2](https://docs.nvidia.com/deeplearning/frameworks/install-tf-jetson-platform/index.html), OpenCV - GPU, Ros-Navigation Stack, Rosserial)
3. ROSMelodic-PROS connection (JetsonNano-VBrain) by using rosserial. [Reference](https://www.vexforum.com/t/use-ros-to-talk-to-the-cortex-or-v5-brain/49818)
[Code section](https://github.com/RoBorregos/VEXU/tree/main/microcontrollers/vexu-v5-pros), using `Comando: rosrun rosserial_python serial_node.py _port:=/dev/ttyACM1 _baud:=115200`
4. Connection ROSMelodic(JetsonNano)-ArduinoUno using [rosserial](Referencia: http://wiki.ros.org/rosserial_arduino/Tutorials)
[Code section](https://github.com/RoBorregos/VEXU/tree/main/microcontrollers/sensors) using `rosrun rosserial_python serial_node.py _port:=/dev/ttyACM2 _baud:=115200`
