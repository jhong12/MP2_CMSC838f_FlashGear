# MP2_CMSC838f_FlashGear
Mini project 2 - FlashGear

## Description
The 'Arduino_sensor' is Arduino code working with 9DOF IMU sensor. It measures the angle of the blades and turns on LEDs with the color calculated from the angle.

The 'Arduino_time' is Arduino code working wihout 9DOF IMU sensor. It regulary turns on/off LEDs multiple times in very short time.

## How to run
You can download one of the two directories.
1) Arduino_sensor
Open Razor_AHRS.ino file and upload to Arduino UNO.

2) Arduino_time
Open Arduino_time.ino file and upload to Arduino UNO.

## References
The Arduino code for 9DOF IMU sensor stick is from here.

https://github.com/ptrbrtz/razor-9dof-ahrs/wiki/Tutorial

The library to control LED strips is from here.

https://github.com/adafruit/Adafruit_NeoPixel
