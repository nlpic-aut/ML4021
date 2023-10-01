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

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Location and Time

- **Department of Mathematics and Computer Science - R.311**
- Saturday and Monday 10:45AM - 12:15AM
- Final exam date: Saturday, 1402/10/23: 9:00AM
                 

Do you use programming to solve problems in your field of study? Do you know enough to be dangerous, but wish you could be proud of your code? This course aims to provide students with sufficient knowledge and skills to use programming as part of their work. In this class, you will learn how to identify and find problems in your code. You will learn to read, parse, organize, and transform data. We will teach you to write code collaboratively and refine your programs so others can use them.The course will be a mixture of lecture and guided exercise with a recitation focused on hands on instruction. In this course, students are expected to have been exposed to some basic programming concepts, such as variables, if-statements, loops, and arrays. However, students are not expected to have extensive programming experience. This course is not appropriate for students that have completed more than two courses involving programming. We expect students in this class to have diverse backgrounds and experience. Some students will be self-taught, while others will have taken a programming course such as 02-201, 15-110, 95-898, or the library’s Software Carpentry workshop. 

### Learning Goals
The goal of the course is to provide an overview of machine learning, which includes the following topics:

 - Practical aspects, such as various learning algorithms like decision trees, neural networks, and Bayesian networks.
 - General models, including genetic algorithms and reinforcement learning.
 - Theoretical concepts, encompassing related fields in statistics, Bayesian learning, and PAC learning theory.

### Prerequisites

1. Calculus and Statistics
2. Linear Algebra
3. Programming Knowledge


## Structure of the course
Meets twice weekly
Most classes will include both a lecture and a collaborative in-class exercise
There will be weekly homework assignments for students to practice
There will be a summative final project, in which students will integrate the tools and techniques they have learned into a cohesive whole. 

Evaluation in the course will be approximately as follows:
 - Assingnments + Final Project: 40%
 - Final Exam: 40%
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

*The deadline for uploading is one day before the exam.*
Presenting the results, explaining the algorithm, and the implementation method orally.
