---
tools: [SOLIDWORKS, Python, ML, Hardware]
image: /assets/images/nectarfy/nectarfy.jpg
description: Building a beehive to save the bees
---
# Nectarfy

## The Problem
I was at a farmer's market buying honey, when I asked them about how climate change was affecting their business. It was here when I learned about the devastating outlook of bees and all the issues they and their keepers faced. From parasites to pesticides, hotter summers and colder winters, and an ever-growing movement towards monocultures, there was a lot of problems which needed solving given our agricultural reliance on bees. It was this spark which inspired me to work with my classmates, capstone team, and ultimately colleagues to develop Nectarfy.

## The First Iteration

Nectarfy has gone through many iterations since its inception. At first, we aimed to for the following features:
- Detect beehive weight
- Monitor internal temperature
- Monitor beehive orientation (Due to theft and other animals)
- Notify user of full beehive

{% include elements/figure.html image="/assets/images/nectarfy/nbhive.jpg" caption="The First Instrumented Beehive" %}

There features were rudimentary at best, and was done between myself and a classmate as an exercise in firmware development. We used an TI MSP430 and wrote firmware to control a load cell, a servo, and other various sensors. I developed and most of the mechanical mechanisms using a combination of woodworking and 3D printing.

{% include elements/button.html link="https://www.youtube.com/watch?v=sVTf1BaiNfE" text="Video" style="outline-dark" size="lg" %}
{% include elements/button.html link="/assets/pdfs/SmartBeehivePR.pdf" text="PDF Report" style="outline-dark" size="lg" %}

## Customer Discovery
Moving forward, I worked with a team of two other engineers and three business students to further take my idea of combining technology with beekeeping forward. We interviewed and spoke with over 50 beekeepers, to ranging from amateurs to professionals. We worked with faculty and aimed to create a startup, which became Nectarfy.

## Nectarfy, The Second Iteration
After market research, speaking with stakeholders and experts, and getting a new engineering team, we updated the technological scope for our beehive:
- Detect varroa mites (The #1 problem beekeepers face today)
- Treat varroa mites (Chemical fumigation)
- Monitor and control internal beehive climate 
- Monitor moisture
- Automated feeding system
- Mobile application to control and monitor the beehive and interact with experts

These key features were developed into an MVP. I helped build mechanical enclosures for the beehive, and constructed the entire varroa mite detection system.

{% include elements/figure.html image="/assets/images/nectarfy/nmvp.jpg" caption="Nectarfy V1" %}

We also built an app which allowed us to interpret data and control our beehive MVP.

{% include elements/figure.html image="/assets/images/nectarfy/napp.jpg" caption="Nectarfy App" %}

### Varroa Mite Detection System
The varroa mite detection system was based on an array of gas sensors. The theory behind it was that beehives would have a relatively monolithic gaseous composition. With the introduction of varroa mites, that composition would change and therefore could be picked up by gas sensors. After, we planned on building a machine learning model to learn the difference between an infected and non-infected hive.

{% include elements/figure.html image="/assets/images/nectarfy/nvmd.jpg" caption="Varroa Mite Detection System" %}

The system was able to easily distinguish room air and a beehive, and various other chemicals. We aimed to further develop the system with our beekeeping partners.

## Nectarfy, The Pivot
After our MVP, two of us from the original team of six moved into a Startup Incubator to try and bring Nectarfy to life. We conducted further interviews and pivoted from a complete beehive to an attachment, which would allow our device to retrofit on existing beehives. We also scaled back some features from the second iteration such that it could fit in this new streamlined form factor.

{% include elements/figure.html image="/assets/images/nectarfy/nvmp2.jpg" caption="Nectarfy V2" %}

