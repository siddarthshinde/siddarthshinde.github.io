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
  *B.S. in Computer Science (Departmental Honors)*, Aug. 2022 – May 2026  

* **Vasavi College of Engineering**, Hyderabad, India  
  *B.E. in Computer Science and Engineering (transfer)*, Nov. 2021 – Feb. 2022  

Research interests
======
* Quantum computing systems and architectures  
* Quantum computer security and reliability  
* Quantum algorithms and their practical implementation

Research experience
======
* **Undergraduate Research Assistant**              
  CASLAB, Northwestern University, Evanston, IL — Jun. 2025 – Aug. 2025  
  * Developed a KL-divergence–based *information-per-dollar* metric to characterize accuracy–cost tradeoffs on commercial quantum processing units using canonical circuits (e.g., Bell states).  
  * Engineered a reproducible Python pipeline to fetch, normalize, and analyze 200+ quantum jobs across multiple vendors and clouds; computed TVD/KL, aggregated by shots, and produced plots for analysis.  
  * Implemented vendor-aware cost models (e.g., runtime-based and per-shot pricing) to enable cross-hardware comparisons of measurement quality vs. spend.  
  * Maintained JSON/CSV analysis artifacts and figure-export scripts to support reproducibility.  
  * Co-developing a manuscript on cost–accuracy tradeoffs in commercial QPUs.

* **Independent Study – Communication Complexity (CSC 499)**  
  North Carolina State University, Raleigh, NC — May 2024 – Jul. 2024  
  * Studied one-way communication complexity and streaming models, including frequency-moment estimation and sketching algorithms.  
  * Implemented the Flajolet–Martin algorithm in C and evaluated estimation variance under different stream characteristics.  
  * Wrote an internal report summarizing results and outlining open questions for future work.

Manuscripts
======
* S. Shinde and J. Szefer, *Quantum Fidelity-per-Cost: a Metric for Evaluation of Quantum Computing Systems* (in preparation), Northwestern University, 2025.

Teaching experience
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Projects
======
* **QPU Benchmarking Toolkit** — Python, Qiskit Runtime, AWS Braket SDK, qBraid, Matplotlib (Jun. 2025)  
  * Command-line and data pipeline tool to fetch results across vendors, normalize measurement outcomes, compute TVD/KL, and export figures and tables for papers.  
  * Provides modular cost-model components for cross-device comparisons and reproducible configurations for circuits, shots, and devices.

* **RPi Router Instructions Website** — Hugo, GitHub Pages (Nov. 2025)  
  * Co-authored and edited a public documentation [site](https://ethanxu1.github.io/rpiinstructions.github.io/){:target="_blank"} that teaches beginners how to turn a Raspberry Pi into a secure router using RaspAP, including VPN, DNS, and ad-blocking setup.  
  * Maintain the Hugo-based documentation stack and GitHub Pages deployment, updating content as router software and OS images evolve.

* **HACK Hardware, nand2tetris** — HDL (Aug. 2024)  
  * Designed and implemented elementary logic gates, a 16KB memory unit, program counter, and ALU from scratch in HACK HDL following the [nand2tetris](https://github.com/siddarthshinde/nand2tetris-implementation){:target="_blank"} specification.

* **CoffeeMaker** — Java, AngularJS, Spring, Hibernate, MySQL, JUnit (May 2024)  
  * Built a full-stack coffee-ordering web app in a team of five, with 10+ REST endpoints and an AngularJS front end.  
  * Implemented backend authentication with Spring Security and Hibernate; improved perceived performance and reduced load times.

* **Maze** — DOSBox, x86 Assembly (Aug. 2023)  
  * Wrote an 8086 assembly subroutine that navigates a 2D maze in under 5,000 instructions for 20 different mazes (up to 5 KB in size).

* **SpellCheck** — C, Vim, Git (Jul. 2023)  
  * Created a spell-checker in C that dynamically allocates memory for a user-provided dictionary.  
  * Designed a hash function that loads 143,000 words into a hash table in under 100 ms and spell-checks 568,000-word input in under 1 second.

Awards and honors
======
* Dean’s List, all semesters, North Carolina State University

Technical skills
======
* **Languages:** Python, C, Java, JavaScript, SQL, x86 Assembly, HTML/CSS  
* **Libraries/Frameworks:** NumPy, Pandas, Matplotlib, Qiskit, Spring, Hibernate, AngularJS, JUnit  
* **Tools/Platforms:** Git, Docker, Linux, ROS

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

