---
title: "Quantum Fidelity-per-Cost: A Metric for Evaluation of Quantum Computing Systems"
collection: publications
category: conferences
permalink: /publications/quantum-fidelity-per-cost/
excerpt: "A metric for comparing cloud quantum computers that accounts for monetary cost alongside output fidelity, applied to 12 physical QPUs across four providers."
date: 2026-07-30
venue: "IEEE International Conference on Quantum Computing and Engineering (QCE)"
paperurl: "https://arxiv.org/abs/2607.28572"
citation: "Siddarth Shinde and Jakub Szefer. &quot;Quantum Fidelity-per-Cost: A Metric for Evaluation of Quantum Computing Systems.&quot; <i>IEEE International Conference on Quantum Computing and Engineering (QCE)</i>, 2026. Accepted. arXiv:2607.28572."
redirect_from:
  - /research/quantum-fidelity-per-cost/
  - /publication/2025-08-01-quantum-fidelity-per-cost
  - /publication/2025-08-01-quantum-fidelity-per-cost/
---

Choosing a cloud quantum computer is partly a scientific question and partly an economic one. Providers expose different machines under different billing models, so the device with the best fidelity is not always the best choice once you account for what a run costs.

This paper proposes Quantum Fidelity-per-Cost, a score that combines the Kullback–Leibler divergence of the measured output from the ideal distribution, the shot count, and the monetary cost under a documented billing model. We apply it to 14 cloud QPU access paths, covering 12 physical QPUs, across Amazon Braket, IBM Quantum Runtime, IQM Resonance, and Oxford Quantum Circuits.

Cost-aware rankings turn out to differ from fidelity-only rankings, and the billing model determines how a device's score changes as the shot count grows.

Accepted at IEEE QCE 2026. [Read it on arXiv](https://arxiv.org/abs/2607.28572).
