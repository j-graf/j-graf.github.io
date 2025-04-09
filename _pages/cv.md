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
* Ph.D in Mathematics, North Carolina State University, 2025
* M.S. in Mathematics, North Carolina State University, 2022
* B.A. in Mathematics (Minor in Computer Science), College of the Holy Cross, 2020

Work experience
======
* 2020-2025: Teaching Assistant
  * North Carolina State University
 
Research Interests
======
* General: Algebraic combinatorics, representation theory, number theory, symbolic computation, algebraic geometry
* Specific: Symmetric functions, plethysm, Hall-Littlewood functions, vertex operators, stability properties, Schur's $$Q$$-functions, raising operators, integer partitions
 
Awards and Honors
======
* Norris-Franke-Griggs Award for Teaching
  * North Carolina State University, Spring 2024

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Languages: English, Spanish
* Programming: Macaulay2, Python, Java, C++
