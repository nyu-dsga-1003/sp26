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
  - *PPA* refers to [*Patterns, Predictions, and Actions*](https://mlstory.org/pdf/patterns.pdf) by Hardt and Recht.

This is a tentative schedule and is subject to change.

**Lecture Recordings.** Recordings of the lectures are available to watch on [Brightspace](https://brightspace.nyu.edu/d2l/home/555813). 
Just navigate to the [Brightspace](https://brightspace.nyu.edu/d2l/home/555813) page and then click *Zoom.*

**Math Review.** As stated in the prerequisites, students are expected to have a solid understanding of linear algebra,
probability and statistics, and multivariable calculus for this course. In addition to the resources listed on the [homepage]({{ site.baseurl }}{% link about.md %})
of the site, here are several shorter notes to get you started if you need to review material:

- [_Mathematics for Machine Learning_](https://mml-book.com/) (includes all the topics so you can pick and choose)
- [Probability Review](https://cs229.stanford.edu/section/cs229-prob.pdf)
- [Linear Algebra Review](https://web.stanford.edu/class/cs246/handouts/CS246_LinAlg_review.pdf)

Sam also designed a course the past two summers at Columbia meant to give students a deeper understanding of these 
prerequisites (given that they have already taken them and would like to progress to graduate-level machine learning).
The entire course could be found at this page: [Math for ML](https://samuel-deng.github.io/math4ml_su25/), and lecture
videos can be found in "Video Recordings" on this page.

**Math Review Videos.** We will also occasionally post some *Math Review Videos* after that week's lab depending on lab 
feedback on what students found confusing about the material in that week. Familiarity with all the prerequisites in this
class can definitely feel daunting at times, so the purpose of these review videos are to re-introduce some prereq concepts
or lecture derivations at a slower pace. These are a totally optional extra resource. Hopefully this helps you digest
or page in you may have been rusty on!

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
