---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is my attempt at a personal blog. Hello World!

I am currently pursuing Masters in Computer Science at the Courant Institute of Mathematical Sciences, NYU. For my internship I joined the perception team at Kodiak Robotics working on mult-sensor deep learning models to learn unified semantic representations of surroundings. Before that, I was a Deep Learning Research Engineer at Deepen AI, an autonomous driving tooling company focusing on annotation and callibration capabilities powered by AI models and Computational Geometry.

Interested in autonomous driving, 3D vision, and perception problems. Also have an eye on ML infrastructure work.

Thoughts and Qs from my projects
=====
{% for post in site.portfolio %}
  {% include archive-single.html type="grid" %}
{% endfor %}