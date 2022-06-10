# Kinematic_bicycle_model
# Autonomous Vehicle Kinematics and trajectory

## Abstract
```
The bicycle model takes a 4-wheel model and combines the front and rear wheels respectively to form a two-wheeled 
model (hence the name bicycle model).
Now instead of dealing with 4 wheels & 2 steering angles we only need to consider 2 wheels and 1 steering angle.
```
## Objective
```
The code is basically written to be implemented in autonomous vehicles to automatically drive on a predefined path or trajectory.
Here in this case the predefined path is _CIRCULAR_.
Our target is to compute state [x, y, 𝜃, 𝛿], 𝜃 is heading angle, 𝛿 is steering angle.
Our inputs are [𝑣, 𝜑], 𝑣 is velocity, 𝜑 is steering rate.
Where,
 sigma = steering angle
 theta = heading angle
 v = velocity
 w = turning rate
 r = radius traced by instantaneous center
 delta = steeing rate
 x_c,y_c = centre of gravity
 w = omega = steering angle rate
 inputs = [v,w]
 inputs are the bicycle speed  𝑣  and steering angle rate  𝜔 .
 The input can also directly be the steering angle  𝛿  rather than its rate in the simplified case. 
 ```
 # Libraries used
 ```
 Numpy
 Matplotlib
 ```
 ## Resulted Image
 ![image](https://user-images.githubusercontent.com/88721277/172982084-c9963733-cf13-4526-b143-83a244d02d1a.png)

