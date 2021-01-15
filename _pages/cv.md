---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* 2017 - Present: Assistant Professor of Oceanography Naval Postgraduate School

* 2014 - 2017: Research Assistant Professor, Applied Research Laboratory, The Pennsylvania State University

* 2012 - 2014: Graduate Fellow, National Defense Science and Engineering Graduate Fellowship Program

Education
======
* Ph.D in Acoustics, The Pennsylvania State University, 2014
* A.B. in Physics, Vassar College, 2009

Publications
======
<style>ol.bibliography li { list-style: none }</style>
{% bibliography --file mypapers %}


Teaching (All at NPS)
======

<ul>{% for post in site.teaching %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
