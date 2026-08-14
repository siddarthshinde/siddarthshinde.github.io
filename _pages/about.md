---
permalink: /
layout: home
description: "Quantum computing systems researcher and incoming Northwestern Computer Engineering Ph.D. student."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% assign profile = site.data.profile %}

<section class="home-hero" aria-labelledby="home-title">
  <div class="home-hero__copy">
    <p class="eyebrow">Quantum computing systems · security · algorithms</p>
    <h1 id="home-title">Researching quantum computers as systems—not just circuits.</h1>
    <p class="home-hero__lead">{{ profile.headline }}, {{ profile.status | downcase }}. {{ profile.summary }}</p>
    <div class="button-row" aria-label="Primary links">
      <a class="button button--primary" href="/research/">Explore my research <span aria-hidden="true">→</span></a>
      <a class="button button--secondary" href="/files/cv.pdf">Download CV <span class="sr-only">as PDF</span></a>
    </div>
  </div>
  <div class="home-hero__portrait-wrap">
    <div class="portrait-accent" aria-hidden="true"></div>
    <img class="home-hero__portrait" src="/images/profile-640.jpg" alt="Portrait of Siddarth Shinde" width="640" height="640" fetchpriority="high">
    <p class="portrait-caption"><span class="status-dot" aria-hidden="true"></span> Incoming Ph.D. student · Northwestern ECE</p>
  </div>
</section>

<section class="home-highlights" aria-labelledby="highlights-title">
  <div class="section-heading">
    <p class="eyebrow">Now</p>
    <h2 id="highlights-title">Current highlights</h2>
  </div>
  <div class="card-grid card-grid--three">
    <article class="feature-card feature-card--publication">
      <p class="card-kicker"><span class="tag tag--success">Accepted</span> IEEE QCE 2026</p>
      <h3>Quantum Fidelity-per-Cost</h3>
      <p>A cost-aware way to compare cloud quantum computers across heterogeneous providers and billing models.</p>
      <a class="text-link" href="{{ profile.publications[0].detail_url }}">Read about the paper <span aria-hidden="true">→</span></a>
    </article>
    <article class="feature-card">
      <p class="card-kicker">Summer 2026</p>
      <h3>Quantum Computing Intern</h3>
      <p>Working with the Data Science team at <strong>apexanalytix</strong> in Greensboro, North Carolina.</p>
      <a class="text-link" href="/research/#experience">View experience <span aria-hidden="true">→</span></a>
    </article>
    <article class="feature-card">
      <p class="card-kicker">Northwestern University · 2026</p>
      <h3>Royal E. Cabell Fellow</h3>
      <p>Beginning a Ph.D. in Computer Engineering at Northwestern University in September 2026.</p>
      <a class="text-link" href="/cv/#awards">View CV <span aria-hidden="true">→</span></a>
    </article>
  </div>
</section>

<section class="split-section" aria-labelledby="research-focus-title">
  <div class="section-heading section-heading--sticky">
    <p class="eyebrow">Research focus</p>
    <h2 id="research-focus-title">From hardware access to useful evidence.</h2>
    <p>I’m interested in evaluation methods that help researchers and practitioners reason about real quantum systems.</p>
  </div>
  <div class="interest-list">
    {% for interest in profile.interests %}
    <div class="interest-item">
      <span class="interest-item__number" aria-hidden="true">0{{ forloop.index }}</span>
      <h3>{{ interest }}</h3>
    </div>
    {% endfor %}
  </div>
</section>

<section class="home-projects" aria-labelledby="projects-title">
  <div class="section-heading section-heading--inline">
    <div>
      <p class="eyebrow">Selected work</p>
      <h2 id="projects-title">Projects beyond the paper</h2>
    </div>
    <a class="text-link" href="/projects/">All projects <span aria-hidden="true">→</span></a>
  </div>
  <div class="card-grid card-grid--two">
    {% for project in profile.projects %}
    <article class="project-card">
      <div class="project-card__meta"><span>{{ project.year }}</span></div>
      <h3>{{ project.title }}</h3>
      <p>{{ project.description }}</p>
      <ul class="tag-list" aria-label="Technologies used">
        {% for technology in project.technologies %}<li class="tag">{{ technology }}</li>{% endfor %}
      </ul>
      {% if project.report %}<a class="text-link" href="{{ project.report }}">Read the report <span aria-hidden="true">↗</span></a>{% endif %}
    </article>
    {% endfor %}
  </div>
</section>

<section class="contact-band" aria-labelledby="contact-title">
  <div>
    <p class="eyebrow">Connect</p>
    <h2 id="contact-title">Interested in quantum systems research?</h2>
  </div>
  <div class="button-row">
    <a class="button button--light" href="mailto:{{ profile.email }}">Email me</a>
    <a class="button button--ghost" href="{{ profile.links.github }}">GitHub <span aria-hidden="true">↗</span></a>
  </div>
</section>
