---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /resume/
  - /resume.html
  - /resume-json
  - /resume-json/
  - /cv-json
  - /cv-json/
---

{% include base_path %}

A [PDF version]({{ base_path }}/files/cv.pdf) of this page is also available.

## Education
* Ph.D. in Computer Engineering, Northwestern University, starting September 2026
* B.S. in Computer Science, North Carolina State University, May 2026
  * Computer Science Departmental Honors
  * Minors in mathematics and philosophy

## Research experience
* June–August 2025: Undergraduate Research Assistant
  * Northwestern University, Department of Electrical and Computer Engineering
  * Supervisor: Prof. Jakub Szefer
  * Compared cloud quantum computers across providers under a metric that accounts for cost as well as fidelity.

* May–August 2024: Undergraduate Research Assistant
  * North Carolina State University, Department of Computer Science
  * Supervisor: Prof. Chin Ho Lee
  * Studied one-way communication complexity and streaming algorithms, and implemented frequency-estimation methods in C.

## Industry experience
* Summer 2026: Quantum Computing Intern
  * apexanalytix, Data Science team
  * Greensboro, North Carolina

## Teaching experience
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Awards and fellowships
* Royal E. Cabell Fellowship, Northwestern University, 2026

## Technical skills
* Languages: Python, Java, JavaScript/TypeScript, C, SQL, x86 assembly
* Quantum: Qiskit, AWS Braket, IBM Quantum
* Tools: Git, Docker, Linux, Flask, React, Spring, Hibernate, JUnit, ROS
