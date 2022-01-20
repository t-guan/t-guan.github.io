---
layout: project
title: IoT SmartHome
description: Building a DIY Smarthub for complete control of home IoT devices.
image: assets/images/hassio.jpg
youtubeId: 
tile_ECE: true
---

Smarthomes have become a more prevalent part of our everyday lives, and I, too, was swept up in the hype. However, I was pretty adverse to letting private companies access to my own data through smart voice devices, as well as the data it could collect from the sensors I would use. So,
I decided to take matters into my own hands and build my own smarthub device. 

I used a Raspberry Pi which runs a Python-based program known as HassIO to act as a hub for consolidating wireless devices around the home. 
To create automations, I wrote script in yaml format in order to create automations and scripts for the smart home devices. Such actions include turning on lights then motion is detected, forcing the lights to change based on the time of day to act as reminders for thing such as waking up or going to sleep. 
The base code which tempates were written on were written in Python. 


Because there were devices using various communication protocols, I needed a way to consolidate them all. I decided to use Zigbee devices and thus needed a ZigBee sniffer tool to find and communicate with smart devices running on the ZigBee network, such as Ikea Lightbulbs, smart switches, motion sensors, and various remotes and buttons.
After connecting them to my Raspberry Pi using the sniffer, I was then able to override existing functions within each device and tailor them to my own preferences.

One of the issues I ran into while setting this up came mostly from configuring the order of execution for various automations. If one automation was to occurr at the same time as another, I had to ensure that my system know what to prioritize over another. 
I reolved this issue by testing every automation I had and ensured it conicded with another, and carefully wrote out a predetermined order for each automation.

As an addition to the IoT smart devices, I also created a data server for the home and personal use. This allows for mass storage of files I work with, especially while at school, avoiding Google Drive storage cap limits and security concerns.

Finally, I added geotagging as well as routing my device through a DNS service, so I could check in on my home outside my local network, and allow the home to automatically turn on lights and other IoT device upon my arrival to my home.

