# gimbal-python
Engineering student project. 3-axis brushless gimbal using MicroPython, a MPU9250 IMU and L6234 motor controller

The main idea is to implement the complementary filter to merge data from the IMU sensors, in order to get the most accurate 3D position of it, and then to use this information to control the brushless motors using SPWM or SVPWM (see Wikipedia)
