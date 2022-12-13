---
name: Hazardous Enviornment Robot, Squishy Robotics
tools: [SOLIDWORKS, Python, Hardware]
image: /assets/images/squishy/squishy.jpg
description: Developing a robot for methane detection in hazardous enviornments
---

# Squishy Robotics, Hazardous Enviorment Robot

## The Problem
Squishy Robotic's platform allows their robots to carry payloads and be dropped from the sky into hazardous locations from a thousand feet in the sky. Our team was tasks to build a new payload to help detect methane gas to be used in detecting leaks for the oil and gas industry.

## My Work
My work on this project involved creating the optical gas imaging sensor which is to be used as the primary form of gas detection. This sensor would be built onto a pan-tilt system which will be integrated into a Squishy Robotics Payload. This payload is the main goal for my contribution to this project.

{% include elements/figure.html image="/assets/images/squishy/spayload.jpg" caption="Example Squishy Robotics Payload" %}

### The Optical Gas Imaging (OGI) Sensor
Primarily, the work done on this sensor was to build and tune an electric circuit which would allow us to readily read and interpret sensor data with a microcontroller. I designed a transimpedance amplifier circuit was designed and tuned for the sensor in conjunction with a lens to block out specific wavelengths of light not relevant to methane.

{% include elements/figure.html image="/assets/images/squishy/sltspice.jpg" caption="Rudimentary Simulation Schematic" %}

### The Pan-Tilt Mechanism
The OGI Sensor would be put onto a pan-tilt mechanism to allow the OGI to scan over a large area for methane detection. I created a 3D model of the pan-tilt mechanism and built a test housing for the whole mechanism. This mechanism will allow me to help write the control schema for the payload, and further develop the mechanism to be suited for the OGI sensor system.