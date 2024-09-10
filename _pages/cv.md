---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF of my CV](/files/Zack_Almquist_CV.pdf)


Education
======
* Ph.D in Sociology, University of California, Irvine, 2013
* M.A. in Demography, University of California, Irvine, 2008
* M.S. in Statistics, Northwestern University, 2007
* B.S. in Mathematics, University of Oregon, 2005

Primary Appointments
======
* University of Washington
  * Associate Professor of Sociology
  * Adjunct Associate Professor of Statistics
  * Senior Data Science Fellow, eScience

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Up Coming Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Current Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Current Service and leadership
======
*  Graduate Committee
*  Human Subjects Liason, Department of Sociology
*  Editor-in-Chief Journal of Mathematical Sociology
