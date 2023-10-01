---
layout: home
title: Machine Learning
nav_exclude: true
seo:
  type: Course
  name: Machine Learning
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}


<!-- <img src="assets/images/logo.png" > 

## Welcome to Machine Learning Course Page -->

### Location and Time

- **Location :** Department of Mathematics and Computer Science - R.311
- **Time :** Saturday and Monday 10:45AM - 12:15AM
- **Final Exam:** Saturday, 1402/10/23, 9:00AM
                 

### Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


## Course Overview

Welcome to the Course of Machine Learning, one of the most exciting and rapidly evolving fields in computer science and data analysis. This course is offered at Amirkabir University of Technology in the Department of Mathematics and Computer Science, is designed to provide you with a comprehensive understanding of the principles, algorithms, and applications of machine learning.

Machine learning has revolutionized industries ranging from healthcare to finance to entertainment. In this course, you will embark on a journey to explore the theoretical foundations and practical applications of machine learning. This course is structured to accommodate students with varying levels of prior knowledge, from those new to programming to those with more advanced technical backgrounds.


## Learning Goals

 - Practical aspects, such as various learning algorithms like decision trees, neural networks, and Bayesian networks.
 - General models, including genetic algorithms and reinforcement learning.
 - Theoretical concepts, encompassing related fields in statistics, Bayesian learning, and PAC learning theory.

### Prerequisites

1. Calculus and Statistics
2. Linear Algebra
3. Programming Knowledge


## Structure of the course
-Meets twice weekly
-Most classes will include both a lecture and a collaborative in-class exercise
-There will be weekly homework assignments for students to practice
-There will be a summative final project, in which students will integrate the tools and techniques they have learned into a cohesive whole. 

Evaluation in the course will be approximately as follows:
 - Assingnments + Final Project : 40%
 - Final Exam : 40%
 - Presentation of a paper + implementation : 20%

## Assignments and Projects

* Each assignment includes both theoretical and implementation aspects.
* Implementation of learning algorithms: At the end of each chapter, using Python.
* For each assignment, you are required to submit a written report, including: answers to questions, a summary of the tasks performed, the algorithm implementation approach, and the obtained results.
* The code should be submitted via the LMS.
* There will be **no deadline** extensions.

## Presentation of a Paper and Implementation

The project consists of four parts:

1. Selecting a research paper related to the thesis topic and obtaining approval (before the month of Aban).
2. Presentation of the chosen paper (starting from the middle of Aban).
3. Designing the relevant algorithms and implementing them.
4. Uploading the implementation results along with a written report on the website.

**The deadline for uploading is one day before the exam.**

Presenting the results, explaining the algorithm, and the implementation method orally.
