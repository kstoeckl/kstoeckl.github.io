---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Pdf: ...

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

Talks
-----
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
