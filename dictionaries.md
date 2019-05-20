---
layout: default
title: Dictionaries
---

# Dictionaries

{% for dict in site.dictionaries %}
* [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) ({{ dict.author }}, {{ dict.year }}) \\
  [{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}
{%- endfor %}

