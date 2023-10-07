---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a PhD student at the Stanford Institute for Computational and Mathematical Engineering (ICME), advised by [Marco Pavone](https://web.stanford.edu/~pavone/). I received my B.S. from Caltech in 2018, where I double majored in [Mathematics](https://www.pma.caltech.edu/research-and-academics/mathematics/math-undergraduate-studies/undergraduate-math-program-description) and [Business, Economics, & Management](https://www.hss.caltech.edu/undergraduate-studies/bem), and minored in [Control & Dynamical Systems](https://www.cms.caltech.edu/academics/ugrad/ugrad_cds_minor). I have completed research internships with the [USRA-NASA Quantum Artificial Intelligence Laboratory](https://riacs.usra.edu/quantum/qacademy) and the [Amazon Modeling & Optimization team](https://www.amazon.jobs/en/teams/mop).

Contact: rabrown1 \[at\] stanford \[dot\] edu
## Research
I am broadly interested in optimization, with various applications including quantum computing, multi-agent control, machine learning, and supply chain management.

My most recent focus involves the design and analysis of hybrid algorithms that leverage the capabilities of the [Coherent Ising Machine](https://cohesing.org). This research aims to provide insights for the synergistic co-design of "hardware primitives" and optimization algorithms, and has applications in [neural network verification](publications/UnifiedSDPVerification). Additionally, I investigate the integration of classical optimization methods into unconventional computing architectures.

Additional topics I have worked on include distributed optimization for multi-agent systems, and reinforcement learning for supply chain management.

## Preprints
{% for post in site.preprints reversed %}
  {% include archive-single-paper.html %}
{% endfor %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}

{% include base_path %}
