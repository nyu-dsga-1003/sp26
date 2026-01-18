---
layout: home
title: About
permalink: /
description: >-
    Course policies and information.
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
**NOTE:** This site is still under construction and will be undergoing changes until the first week of class, on January 20th!
Please stay tuned for updates and monitor your email for communication about the course.

## What's this course?

This course is a graduate-level introduction to machine learning. We try to present machine learning as a story where many algorithmic techniques drop out of a common statistical learning framework. 

The course covers a wide variety of topics in machine learning and statistical modeling. While mathematical methods and theoretical aspects will be covered, the primary goal is to provide students with the tools and principles needed to solve the data science problems found in practice. This course will serve as a foundation of knowledge on which more advanced courses and further independent study can build. A tentative syllabus for the course can be found [here](https://docs.google.com/document/d/1d68yufO1T0G3GzYSnjSGWO84bxAhz7RmTtgS4U3Euf0/edit?usp=sharing).

A key “subplot” of the course is the proliferation of data as historically driving machine learning progress and how it has obviated considerations of bias-variance “tradeoffs”. As we’ve hit upon more and more available data to train models, we could relax our inductive biases more and more. Another goal of this course is to make clear how the proliferation of large-scale data has naturally led us to our current, modern techniques.

If you're a student, all content, logistics, and materials will be available on this page for ease of access (check here first instead of Brightspace). All course announcements will be on [Ed Discussion](https://edstem.org/). Please see [Course Content]({{ site.baseurl }}{% link content.md %}) for the lecture material and problem sets.

**Acknowledgment:** Much of the material of this course (especially Weeks 1-11) are adapted from DS-GA 1003 developed originally by David S. Rosenberg and later adapted by He He, Tal Linzen, Mengye Ren, and others. 

## Prerequisites
This course requires some basic introductory knowledge of machine learning (ML) at the level of understanding the basic ML pipeline
from a "black-box" perspective (i.e., train-test split, cross-validation, evaluating a model, etc.). This should be familiar if students have taken DS-GA 1001 and DS-GA 1002; if there are concerns, please
email the instructors. An pre-recorded introductory "black-box machine learning" lecture will also be uploaded during the first week as 
a primer for students looking to refresh this knowledge as the course begins.

- **Solid mathematical background.** Equivalent to a 1-semester undergraduate course in: linear algebra, multivariable calculus, and statistics.
- **Programming background.** Ability to program in Python is required for most assignments.
- **DS-GA 1001: Introduction to Data Science** (or equivalent)
- **DS-GA-1002: Probability and Statistics for Data Science** (or equivalent)
- *Recommended, but not required:* At least one advanced, proof-based mathematics course.

Machine learning is a confluence of different subjects, but the three most important foundational mathematical subjects for understanding
machine learning are: linear algebra, multivariable calculus, and probability. A free recommended resource for refreshing these subjects
is [_Mathematics for Machine Learning_](https://mml-book.com/) by Deisenroth, Faisal, and Ong. Several other resources for brushing up on
these subjects are:

### Linear Algebra
- *Linear Algebra and Applications* by Gilbert Strang
- [Gilbert Strang's MIT Course on Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- *Linear Algebra Done Wrong* by Sergei Treil, available free as [PDF here](https://www.math.brown.edu/streil/papers/LADW/LADW.html)
- [Daniel Hsu's course notes for Computational Linear Algebra](https://www.cs.columbia.edu/~djhsu/CLA/)
- [3Blue1Brown's Essence of Linear Algebra videos](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### Multivariable Calculus
- [MIT OpenCourseware course on multivariable calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/)
- *Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach* by Barbara Burke Hubbard and John H. Hubbard.
- *Vector Calculus* by Susan Jane Colley

### Probability Theory and Statistics
- [*Probability and Statistics for Data Science*](https://www.ps4ds.net/) by Carlos Fernandez-Granda
- [*Introduction to Probability for Computing*](http://www.cs.cmu.edu/~harchol/Probability/book.html) by Mor Harchol-Balter
- [*Introduction to Probability*](https://projects.iq.harvard.edu/stat110/home) by Joseph K. Blitzstein and Jessica Hwang.
- *A First Course in Probability*  by Sheldon Ross.

## Logistics
- **Lecture Time:** Tuesdays 2:45-4:45PM (in-person)
  - **Lecture Location:** 36 E 8th St (Cantor Film Ctr) Room 200
- **Lab Time:** Thursdays 7:10-8PM (in-person)
  - **Lab Location:** 238 Thompson St (GCASL) Room C95
- **Instructor Office Hours:** 
  - Sam: Tuesdays 5:00pm - 6:00pm (after class in CDS Office 242); Wednesdays 1:00pm - 2:00pm (CDS Office 242)
  - Nick:
  - For section leader office hours, check the [Staff]({{ site.baseurl }}{% link staff.md %}) page of the site
  - For changes in office hours, please keep an eye out on [Ed](https://edstem.org/) and the [Calendar]({{ site.baseurl }}{% link calendar.md %}) page of the site.
- **Announcements and Discussion:** All course announcements and discussion will be handled on [Ed Discussion](https://edstem.org/). Instead of emailing the instructor and instructional staff, please post your questions on [Ed](https://edstem.org/). We will also be using [Ed](https://edstem.org/) for all class-related announcements, so please check your email and [Ed Discussion](https://edstem.org/) frequently to keep up to date with any class logistics/changes/etc.

## Resources

The course does not have any official or required textbooks. All slides will be published before each lecture in [Course Content]({{ site.baseurl }}{% link content.md %}) so students can follow along during lecture. However, we recommend the following optional resources:

- [_Elements of Statistical Learning_](https://hastie.su.domains/ElemStatLearn/) by Hastie, Tibshirani, and Friedman
- [_Pattern Recognition and Machine Learning_](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/) by Bishop
- _Pattern Classification_, by Duda, Hart, Stork
- [_Patterns, Predictions, and Actions_](https://mlstory.org) by Recht and Hardt
- [_Understanding Machine Learning_](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shalev-Shwartz and Ben-David
- [_Boosting: Foundations and Algorithms_](https://direct.mit.edu/books/oa-monograph/5342/BoostingFoundations-and-Algorithms) by Schapire and Freund

We will sometimes post recommended optional reading from these textbooks or a free online source in the [Course Content]({{ site.baseurl }}{% link content.md %}) page of the site. 

## Assessment

There will be a total of 6-7 biweekly homework assignments. We will also have a midterm exam, as well as a final project. The grading breakdown is as follows:

- Homeworks: 20%
- Midterm Exam: 35%
- Final Project: 35%
- Lab Attendance: 10%

**Homeworks.** There will be a total of 6-7 biweekly homework assignments with a mix of theoretical problems and coding problems. For details about the homework assignments, please see the [Homework]({{ site.baseurl }}{% link homework.md %}) page of this site.

**Midterm Policy.** The in-class midterm during the usual lecture slot on **Tuesday, March 10, 2026 2:45pm - 4:45pm ET**. Please
make sure you are available in-person on this day!

Due to resource constraints, we will not be able to allow make-up midterms for those who
cannot attend lecture on that day, so missing the midterm will result in a zero for the
midterm. If you must miss the midterm due to an unexpected emergency or extenuating
circumstance (and do not want to continue the course with a grade of zero on the midterm),
you should bring this up with the instructors as soon as possible so we can possibly arrange
assigning you a grade of “Incomplete.”

**Lab Attendance.** Although lecture attendance is optional (though strongly recommended), lab attendance is an easy part 
of your final grade. For each lab you attend, you will get 1 point; the lab attendance portion of your grade is then simply the
number of labs you attended divided by 10. There are more than 10 labs in the course, so you can miss some of them and
still get full credit. Attending more than 10 labs will give you a slight boost to your grade, as the 10% of your grade
dedicated to lab attendance will weight *X/10* labs, where *X > 10*. We will be tallying lab attendance in-person through a
QR code -- it is your responsibility to make sure that you sign in at each lab session you attend.

**Final Project.** More details about the final project will be provided as the semester progresses!