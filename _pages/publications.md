---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

## Our Research Group
[Research Centre for the Mathematical Foundations of Generative AI (CMFAI)](https://www.polyu.edu.hk/ama/cmfai/)

## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
