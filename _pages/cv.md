---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
description: "Curriculum vitae for Siddarth Shinde, incoming Northwestern Computer Engineering Ph.D. student."
author_profile: true
redirect_from:
  - /resume
  - /resume/
  - /resume.html
  - /resume-json
  - /resume-json/
  - /cv-json/
---

{% assign profile = site.data.profile %}

<div class="cv-header">
  <p class="page-intro">Research, education, teaching, publications, awards, and selected technical work.</p>
  <a class="button button--primary" href="/files/cv.pdf">Download PDF <span aria-hidden="true">↓</span></a>
</div>

<section class="cv-section" aria-labelledby="education-title">
  <h2 id="education-title">Education</h2>
  {% for item in profile.education %}
  <article class="cv-entry">
    <div class="cv-entry__main"><h3>{{ item.institution }}</h3><p>{{ item.degree }}</p>{% if item.details %}<p class="muted">{{ item.details }}</p>{% endif %}</div>
    <div class="cv-entry__meta"><strong>{{ item.date }}</strong><span>{{ item.location }}</span></div>
  </article>
  {% endfor %}
</section>

<section class="cv-section" aria-labelledby="research-title">
  <h2 id="research-title">Research experience</h2>
  {% for item in profile.research %}
  <article class="cv-entry">
    <div class="cv-entry__main"><h3>{{ item.role }}</h3><p>{{ item.institution }} · {{ item.department }}</p><p class="muted">Supervisor: {{ item.supervisor }}</p><p>{{ item.summary }}</p></div>
    <div class="cv-entry__meta"><strong>{{ item.dates }}</strong><span>{{ item.location }}</span></div>
  </article>
  {% endfor %}
</section>

<section class="cv-section" aria-labelledby="industry-cv-title">
  <h2 id="industry-cv-title">Industry experience</h2>
  {% for item in profile.industry %}
  <article class="cv-entry">
    <div class="cv-entry__main"><h3>{{ item.role }}</h3><p>{{ item.organization }} · {{ item.team }}</p></div>
    <div class="cv-entry__meta"><strong>{{ item.dates }}</strong><span>{{ item.location }}</span></div>
  </article>
  {% endfor %}
</section>

<section class="cv-section" aria-labelledby="publication-cv-title">
  <h2 id="publication-cv-title">Publication</h2>
  {% for item in profile.publications %}
  <article class="cv-publication"><h3><a href="{{ item.arxiv }}">{{ item.title }}</a></h3><p>{{ item.citation }}</p></article>
  {% endfor %}
</section>

<section class="cv-section" aria-labelledby="teaching-cv-title">
  <h2 id="teaching-cv-title">Teaching experience</h2>
  {% for item in profile.teaching %}
  <article class="cv-entry cv-entry--compact">
    <div class="cv-entry__main"><h3>{{ item.course }}: {{ item.title }}</h3><p>Undergraduate Teaching Assistant · Supervisor: {{ item.supervisor }}</p></div>
    <div class="cv-entry__meta"><strong>{{ item.dates }}</strong></div>
  </article>
  {% endfor %}
</section>

<section id="awards" class="cv-section" aria-labelledby="awards-title">
  <h2 id="awards-title">Awards and fellowships</h2>
  {% for item in profile.awards %}<p><strong>{{ item.name }}</strong>, {{ item.institution }}, {{ item.year }}.</p>{% endfor %}
</section>

<section class="cv-section" aria-labelledby="projects-cv-title">
  <h2 id="projects-cv-title">Selected projects</h2>
  {% for item in profile.projects %}
  <article class="cv-project"><h3>{{ item.title }} <span>{{ item.year }}</span></h3><p>{{ item.description }}</p></article>
  {% endfor %}
</section>

<section class="cv-section" aria-labelledby="skills-cv-title">
  <h2 id="skills-cv-title">Technical skills</h2>
  <p><strong>Languages:</strong> {{ profile.skills.languages }}</p>
  <p><strong>Quantum:</strong> {{ profile.skills.quantum }}</p>
  <p><strong>Tools &amp; frameworks:</strong> {{ profile.skills.tools }}</p>
</section>
