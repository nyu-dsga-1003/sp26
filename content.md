---
layout: page
title: Course Content
description: Listing of course modules and topics.
---

# Course Content

This page includes all the class content for the course thus far. We will update this
page with lecture materials, lab materials, and readings as the class goes on.

The class is roughly split into two parts. The "classical ML" part will concern foundational
techniques and ideas that underlie the subfield of machine learning from a unifying statistical 
learning framework. Sam will be the lecturer in this part. The "modern ML" part will concern
deep learning and techniques that have gained traction in the past decade because of
the proliferation of data and computational power. Nick will be the lecturer in this part.

- Lecture slides can be found by clicking on the lecture title for the appropriate day.
- All the materials and reading on the right column is optional, but reading (a subset of) these materials before each lecture might help digesting the content during lecture.
  - *ESL* refers to [*The Elements of Statistical Learning*](https://hastie.su.domains/ElemStatLearn/) by Hastie, Tibshirani, and Friedman.
  - *UML* refers to [*Understanding Machine Learning: From Theory to Algorithms*](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shalev-Shwartz and Ben-David.
  - *ISL* refers to [*An Introduction to Statistical Learning*](https://www.statlearning.com/) by James, Witten, Hastie, and Tibshirani.

This is a tentative schedule and is subject to change.

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
