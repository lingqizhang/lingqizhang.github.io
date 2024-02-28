---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /about/
  - /about.html
---

{% include base_path %}

Education
======
* Ph.D in Mathematics and Computing Science, Tokyo Institute of Technology, 2023 
* M.S. in Computer Science and Technology, South China University of Technology , 2017
* B.S. in Computer Science and Technology, South China University of Technology , 2014

Work experience
======
* Spring 2024: RIKEN Center for Computational Science
  * Postdoc Researcher

Honors and Awards
======
* ACM Complementary Student Member, 2023
* Excellent Student Presentation, 187 HPC workshop, 2022.12
* MEXT, 2018.9-2022.3
* National Scholarship, 2014 – 2015 

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Posters
======
  <ul>{% for post in site.posters reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Workshops
======
  <ul>{% for post in site.workshops reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
