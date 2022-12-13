---
layout: project
title: Warehouse System Software
description: Developing a system which allows users to control an e-commerence-esque warehouse. (Video Demo)
image: assets/images/warehouse.jpg
youtubeId: VTLuXjeUF6s
tile_ECE: true
---

This software project built in C# was to create a warehouse fo an e-commerce platform. It was made to simulate a robot-stocked warehouse. The user would have the ability to order items and check stock of items, an admin could shelve items and configure the warehouse.
They could also control shipping trucks to be incoming and outgoing. Finally, robots would be populated inside the warehouse which would shelve items and ensure no shelf would be too overloaded.
<br/><br/>This project took quite a large amount of work, given that it was built as processes, so each process could be created multiple times. Multithreading was used to control and ensure sycnronization throughout the entire system, and websockets were used to create
a connection between the user and the warehouse, which could allow them to connect and control the warehouses at any time, much like existing e-commerce platforms today.<br/><br/>
<div>
<center>{% include youtubePlayer.html id=page.youtubeId %}