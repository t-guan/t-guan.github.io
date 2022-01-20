---
layout: project
title: AI Defective Part Detector
description: A machine learning model built to visually identify defects in injection molded parts
image: assets/images/AIIM.jpg
tile_ECE: true
---

The main motivation for this project was to build a machine learning algorithmn which would be able to identify issues with injection molded parts.<br/><br/>
The reason why this is important, is because the QA process for some of these machines, especially those at the University are done manually, which can be both tiresome and time consuming.<br/><br/>
With that, we used an injection molder to print about 200 parts for the machine learning model. We refrained upon printing more due to the amount of waste we were generating with the project itself.<br/><br/>
We intentionally created batches of bad and good parts, aiming to create as may varied defects as possible. Once those parts were obtained, we took photos using a camera to train a CNN algorithm.<br/><br/>
Primarly for the architecture, Tensorflow was used in a Python enviornment, where the sript would be running from.<br/><br/>
We managed to ultimately achieve a high degree of accuracy with the system, and it was successfully able to identify defects and alert the user.<br/><br/>
Attached below is the PDF of our report for this project.<br/><br/>

<embed src="https://t-guan.github.io/Portfolio/Projects/pdfs/Inj.pdf" type="application/pdf" style="min-height:100vh;width:100%"/>