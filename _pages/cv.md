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
* BS in Microelectronics, Peking University, 2014
* PhD in EECS, University of California, Berkeley, 2020 (expected)

Work experience
======
* Intern @ Tesla Inc. (2019)

* Intern @ Micron Technology (2018)
  
* Intern @ United Technologies Research Center (2015)
  
Skills
======
* Programming/Scripting Languages
  * C/C++, Python, MATLAB, bash
* Machine Learning Frameworks
  * pyTorch
  * Keras
  * scikit-learn
* Optimization Modeling Frameworks
  * cvxpy
  * yalmip

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
