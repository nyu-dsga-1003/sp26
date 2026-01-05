---
layout: page
title: Course Content
description: Listing of course modules and topics.
---

# Course Content

## Part 1: "Classical" ML (Weeks 1–11)

{% assign sorted_modules = site.modules | sort: 'path' %}
{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-01.md' and filename <= 'week-11.md' %}
{{ module }}
  {% endif %}
{% endfor %}

## Part 2: Modern ML (Weeks 12–16)

{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-12.md' and filename <= 'week-16.md' %}
{{ module }}
  {% endif %}
{% endfor %}
