---
layout: default
title: Dictionaries
---

# Dictionaries
## Latin-Latin dictionaries

{% assign dicts = site.dictionaries | where: "categories","latin" | sort: "title" %}
{% for dict in dicts %}

* [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) ({{ dict.author }}, {{ dict.year }}) \\
  [{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}

## General dictionaries

{% assign dicts = site.dictionaries | where: "categories","general" | sort: "title" %}
{% for dict in dicts %}

* [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) ({{ dict.author }}, {{ dict.year }}) \\
  [{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}
  
{%- endfor %}

## Dictionaries of synonyms

{% assign dicts = site.dictionaries | where: "categories","synonyms" | sort: "title" %}
{% for dict in dicts %}

* [{{ dict.title }}]({{ site.baseurl }}{{ dict.url }}) ({{ dict.author }}, {{ dict.year }}) \\
  [{{ dict.tags | join: ", " }}] {% if dict.comment %}_{{ dict.comment }}_{% endif %}

{%- endfor %}

