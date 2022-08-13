---
layout: project
title: Adaptive Game Controller with MSP430 Microcontroller.
description: Creating a proof of concept adaptive game controller. (Video Demo)
image:
youtubeId: 7juvjBKXK2w
tile_ECE: true
---

<center>{% include youtubePlayer.html id=page.youtubeId %}</center>
As part of one of my university courses, I completed various excerises by writing firmware to a TI MSP430 chip. The chip's datasheets were used to understand the behaviour of the chip and how it could be coded.<br/><br/>
The chip was programmed in C, using Code Composer Studio. A variety of functions were coded, which includes using parts packaged on the chip, using it to communicate via UART to a computer, and using the computer to control the board itself.

The UI on the computer side was written in C#, using Windows Forms. Generally, these forms were used to check what data was being reported from the device and act upon it.

The video below shows the firmware on the board repurposed to act as a game controller. It took a little bit of work to do to bypass anticheat on a few games, as well as fine tuning the firmware to be sensitive to particular types of movement. (Sound Warning)



