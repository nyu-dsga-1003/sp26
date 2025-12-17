---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

## Part 1: "Classical" ML (Weeks 1–9)

{% assign sorted_modules = site.modules | sort: 'path' %}
{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-01.md' and filename <= 'week-09.md' %}
{{ module }}
  {% endif %}
{% endfor %}

## Part 2: Modern ML (Weeks 10–15)

{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-10.md' and filename <= 'week-16.md' %}
{{ module }}
  {% endif %}
{% endfor %}
