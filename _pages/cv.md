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
* B.Tech. in Computer Science and Engineering, IIT Patna, 2012
* Masters in Computer Science, ETH Zurich, 2014
* Ph.D in Computer Science, ETH Zurich, 2020

Work experience
======
* Nov 2020-Aug 2021: Postdoctoral Researcher
  * VMware Research
* Summer 2011: Research Assistant
  * University of New South Wales
  * Supervisor: Professor Arcot Sowmya

* Summer 2010: Research Assistant
  * University of Houston
  * Supervisor: Professor Ioannis A. Kakadiaris
  
Awards
=======
* Sep 2014: ETH Medal for Best Master Thesis
* Dec 2012: Preseident of India Gold Medal, IIT Patna
* Dec 2012: Institute Silver Medal, IIT Patna

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Software
=======
<ul>
  ELINA <a href="http://elina.ethz.ch/"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>
</ul>
<ul>
  ERAN <a href="https://github.com/eth-sri/eran"><i class="fab fa-fw fa-github zoom" aria-hidden="true"></i></a>
</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

