---
title: "Quantum Fidelity-per-Cost"
collection: publications
category: conferences
permalink: /research/quantum-fidelity-per-cost/
redirect_from:
  - /publication/2025-08-01-quantum-fidelity-per-cost
  - /publication/2025-08-01-quantum-fidelity-per-cost/
excerpt: "A cost-aware metric and cross-provider measurement study for evaluating cloud quantum computers."
description: "Quantum Fidelity-per-Cost, accepted at IEEE QCE 2026, compares cloud quantum computers across fidelity, shot count, and monetary cost."
date: 2026-07-30
venue: "IEEE International Conference on Quantum Computing and Engineering (QCE), 2026"
author_profile: true
---

{% assign publication = site.data.profile.publications[0] %}

<div class="paper-header">
  <div class="publication-card__status"><span class="tag tag--success">Accepted</span><span>IEEE QCE 2026 · arXiv:2607.28572</span></div>
  <p class="paper-authors">Siddarth Shinde and Jakub Szefer</p>
  <div class="button-row">
    <a class="button button--primary button--small" href="{{ publication.pdf }}">Read the paper <span aria-hidden="true">↗</span></a>
    <a class="button button--secondary button--small" href="{{ publication.arxiv }}">View on arXiv <span aria-hidden="true">↗</span></a>
  </div>
</div>

## Overview

Cloud quantum computing turns hardware selection into both a scientific and an economic decision. Providers expose different machines through different billing models, so a device that looks best on fidelity alone may not be the most useful choice once cost enters the comparison.

This work presents a cross-provider measurement study spanning **14 cloud QPU access-path entries**, representing **12 physical QPUs**, across Amazon Web Services, IBM Quantum Runtime, IQM Resonance, and Oxford Quantum Circuits.

## Quantum Fidelity-per-Cost

The paper proposes Quantum Fidelity-per-Cost (QFC), a score that combines Kullback–Leibler divergence from an ideal output distribution, shot count, and monetary cost under a documented billing model. The results show that cost-aware rankings can differ substantially from fidelity-only rankings—and that billing models determine how a device’s score scales with shot count.

## Citation

<div class="citation-box">{{ publication.citation }}</div>

<div class="link-row">
  <a class="text-link" href="{{ publication.doi }}">DOI <span aria-hidden="true">↗</span></a>
  <a class="text-link" href="{{ publication.arxiv }}">arXiv abstract <span aria-hidden="true">↗</span></a>
  <a class="text-link" href="{{ publication.pdf }}">PDF <span aria-hidden="true">↗</span></a>
</div>
