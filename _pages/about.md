---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello World! This is my attempt at a personal blog. 

I am currently solving perception challenges at Kodiak Robotics to build and scale autonomous trucks. Most of of my work is on multi-sensor deep learning models to learn unified semantic representations of surroundings. Before Kodiak, I was as a Deep Learning Research Engineer at Deepen AI, an autonomous driving tooling company that focuses on annotation and calibration capabilities powered by AI models and Computational Geometry.

My interests lie in autonomous driving, 3D vision, and perception problems. Additionally, I keep an eye on ML infrastructure work.

Thoughts and Qs from my projects
=====
{% for post in site.portfolio %}
  {% include archive-single.html type="grid" %}
{% endfor %}
