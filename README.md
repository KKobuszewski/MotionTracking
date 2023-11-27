# MotionTracking

Simple project demonstration pricpicles of machine vision and motion tracking.

## Calibration

We assumed motion on a static background. To make simple calibration of a camera to connect real points with cordinates on image we can treat it as a device performing function from 2D to 2D. This function can be interpolated (i.e. as two function from 2D to 1D with scipy.interpolate).

![alt text](https://github.com/KKobuszewski/MotionTracking/blob/main/calibration1.png?raw=true)
![alt text](https://github.com/KKobuszewski/MotionTracking/blob/main/calibration2.png?raw=true)
![alt text](https://github.com/KKobuszewski/MotionTracking/blob/main/calibration3.png?raw=true)

## Motion Tracking
