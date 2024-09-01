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
* Ph.D in Mathematics, University of Alberta, 2016
* M.S. in Mathematics, Queen's University, 2011
* B.S. in Mathematics, Queen's University, 2009

Work experience
======
* January 2019 - present: Assistant Professor, Lehigh University

* February 2016 - December 2018: Research Assistant Professor, University of Miami
  
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
  
