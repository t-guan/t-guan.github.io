---
layout: project
title: Two-Axis Gantry System
description: DC Motor and Stepper motor two-axis gantry
image: assets/images/tag.jpg
---

In this project, the two axis gantry shown in the video was made. It was controlled by a DC and Stepper motor driver board which was hand soldered. The controller on it was a TI MSP430 chip whose firmware was coded in C using Code Composer Studio.<br/><br/>
The axis had a stepper motor which would move a platform perpendicular to the table, and a DC motor which would move a platform which was parallel to the table. A contoller was designed for the DC motor and coded in C onto the 
MSP430 board to ensure it would not overshoot its position by more than 5mm, and would return to its position given any disturbances. The entire gantry was controller via Windows Form, written in C# and using a serial port to 
communicate via UART to the controller. <br/><br/>
The user could imput the desired location of travel, and the PWM for both the stepper and the DC motor in the Windows Form, which would then be read as data packets by the motor controller board, and reflected into the gantry 
system.
