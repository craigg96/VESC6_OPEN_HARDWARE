# VESC6_OPEN_HARDWARE
Open source implementation of the vesc 6 hardware schematics published by Benjamin Vedder. Built in KiCAD and contains JLCPCB component IDs for everthing populated on the board so anyone can order their own!

## Design
* Continuous current: 70A; instantaneous current: 120A (With proper heat sinking)
* STL130N6F7 MOSFETs rated to switch up to 130A, software limits it to 120A.
* Voltage: 10V-60V(Cells: 3-13S)
* Ports: USB, CAN x2, ADC, on/off switch, SWD, Hall Sensors
* LSM6DS3 IMU
* JST-SH connectors (6pin and 4 pin)
* Holes either side of the MOSFETs allow for even clamping of a simple rectangular heatsink.


## Manufacture
* Economy PCBA maufacture can be used without placing the IMU - 5 boards approx £160GBP
* Standard PCBA manufacture with placing the IMU costs more - 5 boards approx £200GBP
* Custom board software build as well as hardware configuration files are available in the software folder.

## Testing so far...
Release 1 has been flashed and fully tested on the bench to verify current feedback, backEMF sensing, temperature sensing and IMU work as expected.
Hardware has been field tested by several months of daily use (ebike) pulling sustained power over 2kW with no issues.

![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/top.png?raw=true "top")
![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/isometric.png?raw=true "isometric")
![image](https://github.com/craigg96/VESC6_OPEN_HARDWARE/blob/main/Images/IMG_20250928_213952.jpg?raw=true "isometric")
