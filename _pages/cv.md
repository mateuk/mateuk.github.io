---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Sc. in Mathematics, Warsaw University of Technology, 2018
* Ph.D. in Computational Linguistics/Computer Science, Charles University, 2020 - now
  * Supervised by [Pavel Pecina](https://ufal.mff.cuni.cz/~pecina/index.html)

Work experience
======
* Summer 2022 - Fall 2022: Applied Scientist Intern
  * Amazon Development Center, Bucharest, Romania
  * Working on Multi-modal Document Understanding

* Summer 2018 - Fall 2020: NLP Engineer
  * Samsung R&D Institute Poland, Warsaw, Poland
  * Working on Machine Translation
  
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
  