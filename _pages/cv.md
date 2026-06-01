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
* M.E. in Electronic Information, Shanghai University
* B.S. in Data Science and Big Data Technology, Zhejiang University of Science and Technology

Research Interests
======
* Mamba-based hyperspectral image classification and reconstruction
* Hyperspectral image classification
* Hyperspectral image reconstruction

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
