---
layout: project
title: Kuka YouBot Manipulation
date: March 2019
image: /public/images/youbot.png
---

## Overview
In this project, I aimulated a mecanum-wheeled-robot’s end-effector to grasp, carry, and drop a cube to specified locations. I used rigid body transformations, forward and inverse kinematics, feedback control, odometry, Python and V-REP sumlator. 


## Demo videos

###Best Test Run:

Feedforward plus PI with at least 30 degrees of orientation error and
0.2 m of position error from the first configuration of the reference
trajectory

**Type of Controller**: feedfoward-plus-PI
**Gains**: Kp = 0.32 , Ki = 280.07009

[![IMAGE ALT TEXT](http://img.youtube.com/vi/DXQIR7oyLqs/0.jpg)](http://www.youtube.com/watch?DXQIR7oyLqs "Best case")


###Overshoot Test Run:
Feedforward plus PI with at least 30 degrees of orientation error and
0.2 m of position error from the first configuration of the reference
trajectory

**Type of Controller**: feedfoward-plus-PI
**Gains**: Kp = 3, Ki = 700

[![IMAGE ALT TEXT](http://img.youtube.com/vi/SJRg97WYugo/0.jpg)](http://www.youtube.com/watch?v=SJRg97WYugo "Overshoot Case") 

###New Task Test Run

Feedforward plus PI with at least 30 degrees of orientation error and
0.2 m of position error from the first configuration of the reference
trajectory

**Type of Controller**: feedfoward-plus-PI
**Gains**: Kp = 0.32, Ki = 225

Initial and Goal Configurations of cube are adjusted, and the new data is shown below:

# initial target configuration
TscInit = np.array([[1,0,0,1],
                    [0,1,0,0.5],
                    [0,0,1,0.025],
                    [0,0,0,1]])
# goal target configuration
TscFin = np.array([[0,1,0,-0.5],
                    [-1,0,0,-1],
                    [0,0,1,.025],
                    [0,0,0,1]])
           
[![IMAGE ALT TEXT](http://img.youtube.com/vi/FwEzuXzw9Dg/0.jpg)](http://www.youtube.com/watch?v=p3Trt9g9HSE "New Task") 

**Note**
Github code not available publicaly due to academic purposes. However, I can speak at length with those who have interests about the technical aspects of the code written for this project. 