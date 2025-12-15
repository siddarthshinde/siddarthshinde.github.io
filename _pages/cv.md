---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **North Carolina State University**, Raleigh, NC  
  *B.S. in Computer Science (Departmental Honors) and Minors in Math & Philosophy*, Aug. 2022 – May 2026  

* **Vasavi College of Engineering**, Hyderabad, Telangana, India  
  *B.E. in Computer Science and Engineering (Transferred out)*, Dec. 2021 – Feb. 2022  

Research interests
======
* Quantum computing systems and architectures  
* Quantum computer security  
* Quantum algorithms  

Research experience
======
* **Undergraduate Research Assistant**  
  Northwestern University, Computer Architecture and Security Lab (PI: Dr. Jakub Szefer), Evanston, IL — Jun. 2025 – Aug. 2025  
  * Developed a KL-divergence–based *information-per-dollar* metric to quantify accuracy–cost tradeoffs on commercial quantum processing units by executing canonical circuits (e.g., Bell states).  
  * Engineered a reproducible Python pipeline to fetch, normalize, and analyze 200+ quantum jobs across vendors/clouds; computed TVD/KL, aggregated by shots, and produced plots.  
  * Implemented vendor-aware cost models (e.g., runtime-based or per-shot pricing) to enable cross-hardware comparisons of measurement quality vs. spend.  
  * Maintained analysis artifacts (JSON/CSV) and figure export scripts for reproducibility.  
  * Co-developing a manuscript on cost–accuracy tradeoffs in commercial QPUs.

* **Independent Study: Communication Complexity (CSC 499)**  
  North Carolina State University, Raleigh, NC — May 2024 – Jul. 2024  
  * Studied one-way communication complexity and streaming models; surveyed frequency-moment estimation and sketching algorithms.  
  * Implemented algorithms in C and authored an internal report summarizing literature and proofs.

Manuscripts
======
* Shinde, S., & Szefer, J. (in preparation). *Quantum Fidelity-per-Cost: a Metric for Evaluation of Quantum Computing Systems.* Northwestern University, 2025.

Teaching experience
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
