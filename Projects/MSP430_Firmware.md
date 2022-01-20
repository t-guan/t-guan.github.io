---
layout: project
title: MSP430 Game Controller
description: Learning to write firmware to achieve various functions on an MSP430 Board. (Video Demo)
image:
youtubeId: 7juvjBKXK2w
tile_ECE: true
---

<center>{% include youtubePlayer.html id=page.youtubeId %}</center>
As part of one of my university courses, I completed various excerises by writing firmware to a TI MSP430 chip. The chip's datasheets were used to understand the behaviour of the chip and how it could be coded.<br/><br/>
The chip was programmed in C, using Code Composer Studio. A variety of functions were coded, which includes using parts internal to the chip, using it to communicate via UART to a computer, and using the computer to control the chip itself.

The UI on the computer side was written in C#, using Windows Forms. Generally, these forms were used to check what data was being reported from the device and act upon it. Eventually, the same board was used on the two-axis gantry system and firmware was written to control the motor system.

The video below shows the firmware on the board repurposed to act as a game controller. It took a little bit of work to do to bypass anticheat on a few games, as well as fine tuning the firmware to be sensitive to various types of movement. (Sound Warning)



