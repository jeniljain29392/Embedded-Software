# Embedded-Software

This repository includes some of my embedded software projects which I implemented 
during my Masters studies.

Folder Structure
- RTOS- Shared queue:

    This folder contains an example of a shared queue which can be used by various 
    tasks to write messages to the RS232 port simultaneously.

- Flight Simulator using Inertial Measurement Unit (IMU):

    Implementation of a flight simulation using a 6-axis gyro & accelerometer IMU. 
    Applied Kalman filter to estimate the position and the orientation of IMU.

- Inter-Processor Communication:

    A series of Linux programing exercise including implementation of a character
    device driver for a shared memory queue and an user application to demonstrate 
    event and signal handling in Linux for a real time systems.

- I2C Driver for an EEPROM chip:

    Developed an I2C client driver for an EEPROM chip to demonstrate read and write 
    operations using work queues and ioctl commands.

- Automatic Parking Indicator:

    Developed a prototype for an automatic parking system. SPI protocol driver for 
    an ultrasonic sensor on intel Galileo board to vary animation on LED matrix 
    based on distance from the obstacle.


