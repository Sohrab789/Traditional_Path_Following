Path Following for Nomoto 1<sup>st</sup> Order Dynamics with LOS Guidance and PID Controller
This repository demonstrates path following for various trajectories such as Straight Line, Circle, Figure Eight, and Random Paths using the Nomoto 1<sup>st</sup> Order Dynamics model. The Line-of-Sight (LOS) guidance system provides steering commands, while a PID Controller adjusts the vessel's heading to follow the desired path. This is particularly useful for simulating maritime navigation or dynamic systems that follow similar control algorithms.

Features
Path Types:
Straight Line
Circle
Figure Eight
Random Paths
Dynamics:
Nomoto 1<sup>st</sup> Order Model
Guidance:
Line-of-Sight (LOS) Algorithm
Controller:
PID Controller for Steering
Visualization:
Plotting results for clear path-following demonstrations
How It Works
The repository simulates a vessel following different paths using three main components:

Nomoto 1<sup>st</sup> Order Dynamics:
Models the system's response to steering commands, capturing the vessel's inertia and turning behavior.
LOS Guidance Algorithm:
Provides the desired heading by calculating the line-of-sight angle to keep the vessel on course toward the next waypoint.
PID Controller:
Corrects steering errors by adjusting the rudder angle based on the difference between the desired and actual heading.
