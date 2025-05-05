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
  * Thesis: Schur's $$Q$$-functions: Pfaffian Construction, Vertex Operator Identity, Plethysm, and Generalizations
  * Advisor: Naihuan Jing
* M.S. in Mathematics, North Carolina State University, 2022
* B.A. in Mathematics, College of the Holy Cross, 2020
  * Thesis: Partitions with Distinct Parts and the Parity of Their Rank
  * Advisor: Cristina Ballantine
  * Minor: Computer Science

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

In Preparation
------
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "inpreparation" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Preprints
------
  <ul>{% for post in site.publications reversed %}
    {% if post.category == "preprint" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Journal Articles
------
  <ol>{% for post in site.publications reversed %}
    {% if post.category == "article" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>
  
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
