---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Pre-Prints:
-----------

<ul>{% for post in site.pre-prints reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Papers:
-------

<ul>{% for post in site.papers reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
