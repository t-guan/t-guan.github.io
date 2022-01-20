---
layout: project
title: Altera DE0-CV Clock and Calculator
description: Learning Assembly on an Altera DE0-CV. (Video Demo)
image: assets/images/altera.jpg
youtubeId: 1KdnRus7AZ8
tile_ECE: true
---

As part of one of my university courses, I completed various excerises by writing assembly machine language to an Intel DE0-CV development board. The main motivation for these projects were to understand how to write machine code, and how it can interact
with hardware.
I used Quartus and VHDL on an Intel Altera DE0-CV Board to code and build various projects. However, before working on the board, I modeled the projects in Multisim using logic gates and other logic tools to simulate the output before writing the machine code. Furthermore, I made some of the circuits myself
using flip flops, logic gates, and a variety of other circuit parts.

Once the fundamentals were covered, I created three projects, a scrolling 7-segment display, a basic calculator, and a 24 hour clock, whose time could be set based on the state of the switches and button presses.
These were developed using Assembly Machine Language, using a compiler which was written and provided by the course instructor. 

The 7-segment display would scroll various messages based on the on/off states of switches. The calculator's demo video is linked below.

<center>{% include youtubePlayer.html id=page.youtubeId %}

