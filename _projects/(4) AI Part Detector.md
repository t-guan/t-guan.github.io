---
name: AI Defective Part Detector
tools: [AI, ML, CV, Injection Molding]
image: /assets/images/aiim/AIIM.jpg
description: Show some support by following me!
external_url: https://github.com/YoussefRaafatNasry
---
# AI Defective Part Detector

# The Problem
The injection molding machine at the University would often be used to repeatedly print out multiple parts for use in labs and projects. These prints would often go unattended, but they had the propensity to fail without supervision. Typically, someone would check in on the machine every hour or so, but sometimes it would be too late and defective parts would already be printed, going to waste. Our team was tasked to develop a system which would use a camera system and AI to monitor the injection molding machine and trigger early warnings in the case of defective parts.

# The Model

We used a camera to take over 200 photos of good and defective parts, labeled and trained a CNN model to analyze each part.

{% include elements/figure.html image="/assets/images/aiim/astruc.jpg" caption="Algorithm Structure" %}

With this model, we were able to set up a camera to accurately detect defective parts and notify the machinist.