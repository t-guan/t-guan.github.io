---
layout: project
title: Two-Axis CNC
description: Controlling a 2D CNC Machine.
image: assets/images/2axisCNC.jpg
tile_MC: true
---

The scope of this project was to apply control theory from the classroom into a practical application. A 2D CNC machine (seen above) was controlled with various control schema, such as PID, Lead-Lag, and Pole Placement. The bottom plate of the machine moved on a X-Y plane, while the pen was held stationary.

MATLAB SIMULINK was first used to simulate and build the controllers. A mathematical model and characteristic equation was developed based on a ball-screw drive table. There was a lot of simplification in this model which created did add some error into both simulation and in practical applications. Testing was done to see which controller performed the best.

Further applying our controllers, I drew a trajectory for the machine to follow which was ultimately drawn onto a piece of paper. The trajectory was written as gcode and outputted into a .mat file. Various controllers were loaded onto the 2D CNC to see how it would perform on drawing the trajectory. The response for one of these controllers compared to the inputted trajectory can be seen below.
<center><img src="ProjectImages/2dCNCcontour.jpg" alt="Closeup of Driver chip" width="400" height="400"></center>

