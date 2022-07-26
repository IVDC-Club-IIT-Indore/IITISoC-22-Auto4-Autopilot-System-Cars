# Autopilot system for _Tesla_ cars

Mentors: [Yeeshukant Singh](https://github.com/Yeeshukant), [Kshitij Bhat](https://github.com/KshitijBhat)

Members : [Aditya Suwalka]( https://github.com/git-suwalkaaditya)

**Description**: While on the highway, the monotonous speed
control is a bit tiresome for drivers (especially for long
distances and longer durations). Lane Assist and Adaptive
Cruise Control (ACC) features can help the drivers in these
situations. Depending on the actions of other
objects/vehicles in the car's immediate vicinity, these
systems can slow down and stop the vehicle when required.

**Specifications**:
- Computer Vision Pipeline for Lane detection should be
efficient in detecting the free path on the road.
- Motion planning and control systems are needed to steer
the vehicle to have the least cross-track error and
automatic lane centering.
- Bonus points for an active obstacle avoidance system to
change lanes and avoid other cars in the lane.

OUR MODEL :
1. A video and screenshots of the demo can be seen in this blog post: https://www.osrfoundation.org/simulated-car-demo/
2. First you need to build the car_demo package:
 
  
$ mkdir -p osrf_car/src
    
$ cd osrf_car/src

$ git clone https://github.com/KshitijBhat/car_demo.git

$ cd ..

$ catkin_make

$ source devel/setup.bash

3. Now to run the simulation:
$ roslaunch car_demo demo.launch

4.To move the car, run the following sample code:
$ rosrun car_demo move.py
