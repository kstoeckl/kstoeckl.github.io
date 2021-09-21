---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Pre-Prints:
-----------

{% for post in site.pre-prints reversed %}
  {% include archive-single.html %}
{% endfor %}

Papers:
-------

{% for post in site.papers reversed %}
  {% include archive-single.html %}
{% endfor %}
