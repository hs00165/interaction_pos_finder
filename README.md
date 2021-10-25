# Interaction Position Finder

### Requirements
- ROOT v6 +
- CubicSpline.h - From Josh Hookers github: https://github.com/joshhooker/CubicSplineClass


### Use
This program uses experimental data using a SuperX3 detector, placed at some radius and z-offset from the target to determine the exact position of the target relative to the detector.

This code takes three inputs from the user to determine this: 

### 1) Data from the detector in two columns:
	   Col 1       |         Col 2
-------------------------------------------------------
	Energy [MeV]   |   z position on detector [0-1]

### 1) The expected kinematics line:
Calculated using Catkin (Other relativistic kinematics calculators are available on the market)
	               Col 1                   |         Col 2
-------------------------------------------------------------------
	Angle [degrees, smallest to largest]   |   Energy [MeV]

### 3) A TCutG gate around the data that corresponds to the state you are fitting to



