---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Computer Science, Lancaster University, 2023 (expected)
* MSc in Computer Engineering, Hacettepe University, 2021
* BSc in Computer Engineering, Ankara Yildirim Beyazit University, 2018
* BSc in Electronics and Communicatoin Engineering, Ankara Yildirim Beyazit University, 2017


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
