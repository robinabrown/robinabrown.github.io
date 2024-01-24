---
title: "Accelerating Continuous Variable Coherent Ising Machines via Momentum"
paperauthors: "R. A. Brown, D. Venturelli, M. Pavone, D. E. Bernal Neira"
collection: publications
permalink: /publication/MomentumCPAIOR
date: 2023-12-15
venue: 'Under Review'
paperurl: 'http://robinabrown.github.io/files/MomentumCPAIOR.pdf'
excerpt: We integrate Adam and momentume optimizers with the continuous variable Coherent Ising Machine (CV-CIM) dynamical solver. We show that both optimization techniques can improve the convergence speed and sample diversity of the CV-CIM, while Adam improves the stability of the resulting system
thumbnail: "ccp_icon.png"
---
The Coherent Ising Machine (CIM) is a non-conventional architecture that takes inspiration from physical annealing processes to solve Ising problems heuristically. Its dynamics are naturally continuous and described by a set of ordinary differential equations that have been proven to be useful for the optimization of continuous variables non-convex quadratic optimization problems. The dynamics of such Continuous Variable CIMs (CV-CIM) encourage optimization via optical pulses whose amplitudes are determined by the negative gradient of the objective; however, standard gradient descent is known to be trapped by local minima and hampered by poor problem conditioning. In this work, we propose to modify the CV-CIM dynamics using more sophisticated pulse injections based on tried-and-true optimization techniques such as momentum and Adam. Through numerical experiments, we show that the momentum and Adam updates can significantly speed up the CV-CIM's convergence and improve sample diversity over the original CV-CIM dynamics. We also find that the Adam-CV-CIM's performance is more stable as a function of feedback strength, especially on poorly conditioned instances, resulting in an algorithm that is more robust, reliable, and easily tunable. More broadly, we identify the CIM dynamical framework as a fertile opportunity for exploring the intersection of classical optimization and modern analog computing.

[paper](http://robinabrown.github.io/files/MomentumCPAIOR.pdf)

### Bibtex

@article{BrownBernalNeiraEtAl2024,
  author    = {Brown, R. A. and Venturelli, D. and Pavone, M. and Bernal Neira, D. E.},
  title     = {Accelerating Continuous Variable Coherent Ising Machines via Momentum},
  year      = {2024},
  url       = {https://arxiv.org/abs/2401.12135}
}
