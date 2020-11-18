# Drowsiness and Yawn detection with voice alert using Dlib

Objective:
- To determine the drowsiness and yawn action of the driver while driving any vehicle
- Simple code in python using OpenCV to detect Drowsiness, Yawn and alert the user using Dlib.

## Dependencies

1. Python 3
2. opencv (tested with 3.4) 
3. dlib	(tested with 19.18.1)
4. imutils (tested with 0.5.3)
5. scipy
6. numpy
7. argparse

## Run 

```
Python3 drowsiness_yawn.py -- webcam 0		//For external webcam, use the webcam number accordingly
```

## Setups

- In my system, I could not install the Visual Studio for Dlib library as it would have taken alot of memory
- And therefore I have used the whl format to overcome this problem
- That whl is only compatible with only Python 3.6 but if you have full visual studio installed, you can use any version of python
- Make a new environment with python 3.6
- try to run the code without any libraries installed
- When you get the error, install the library one by one
- Before "dlib", make sure "cmake" is installed
- for Dlib - use this command "pip install dlib-19.8.1-cp36-cp36m-win_amd64.whl"
- the above dlib file is compatible with python version 3.6 only

Change the threshold values according to your need
```
EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 10`	//change this according to the distance from the camera
```

## Lead
** Rahi Verma **

## Team Members
** Dharmik Trivedi
** Pranit Vithalkar
** Sriranga Ramakrishna


## Acknowledgments





