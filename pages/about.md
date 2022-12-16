---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I'm a UBC Mechanical Engineering Grad, with a focus on Mechatronics.<br> I'm currently studying at UC Berkeley, pursuing my Masters of Engineering with a focus on Product Design. :iphone: <br>
I am passionate about creating elegant products and designs, and developing solutions towards problems with big social impact, with a soft spot for sustainability. :evergreen_tree: <br>
I spend my free time hiking, climbing, singing, and playing Overwatch/Valorant! :video_game:

<div class="row">
{% include about/skills.html title="Hardware Skills" source=site.data.hardware-skills %}
{% include about/skills.html title="Software Skills" source=site.data.software-skills %}
{% include about/skills.html title="Code Languages" source=site.data.programming-skills %}

</div>

<div class="row">
{% include about/timeline.html %}
</div>