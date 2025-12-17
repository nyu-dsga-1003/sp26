---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

## Part 1: "Classical" ML (Weeks 1–10)

{% assign sorted_modules = site.modules | sort: 'path' %}
{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-01.md' and filename <= 'week-10.md' %}
{{ module }}
  {% endif %}
{% endfor %}

## Part 2: Modern ML (Weeks 11–16)

{% for module in sorted_modules %}
  {% assign filename = module.path | split: '/' | last %}
  {% if filename >= 'week-11.md' and filename <= 'week-16.md' %}
{{ module }}
  {% endif %}
{% endfor %}
