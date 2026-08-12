# VESC6_OPEN_HARDWARE
Open source implementation of the vesc 6 hardware schematics published by Benjamin Vedder. Built in KiCAD and contains JLCPCB component IDs for everthing populated on the board so anyone can order their own!

Economy PCBA maufacture can be used without placing the IMU - 5 boards approx £160GBP
So standard PCBA manufacture with placing the IMU costs more - 5 boards approx £200GBP

Release 1 has been flashed and fully tested with all functions working as expected inclusing the IMU.
Custom board software build as well as hardware configuration files are available in the software folder.

Hardware has been tested by several months of daily use pulling peak power over 1500W with no issues.
MOSFETS used are rated to switch up to 130A, software limits it to 120A.
Holes either side of the MOSFETs allow for even clamping of a simple rectangular heatsink.

![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/top.png?raw=true "top")
![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/isometric.png?raw=true "isometric")
![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/IMG_20250928_213952.jpg?raw=true "isometric")
