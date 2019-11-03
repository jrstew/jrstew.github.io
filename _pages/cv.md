---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF of my CV can be found <a href="https://jrstew.github.io/files/cv.pdf">[HERE]</a>.

Education
======
* B.A. in Statistics, Rice University, 2013
* M.A. in Statisttics, Rice University, 2018
* Ph.D in Statistics, Rice University, 2020 (expected)

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
  
Software 
======
<ul>
  <li><a href="https://cran.r-project.org/package=mlergm">mlergm</a> - Multilevel Exponential-Family Random Graph Models (Author, Creator, Maintainer)</li>
  <li><a href="https://cran.r-project.org/package=hergm">hergm</a> - Hierarchical Exponential-Family Random Graph Models (Author)</li>
</ul>

 
