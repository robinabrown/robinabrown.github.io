---
title: "A Copositive Framework for Analysis of Hybrid Ising-Classical Algorithms"
paperauthors: "R. A. Brown, D. E. Bernal Neira, D. Venturelli, M. Pavone"
collection: publications
permalink: /publication/CopositiveIsing
date: 2023-03-01
venue: 'Under Review'
paperurl: 'http://robinabrown.github.io/files/CopositiveIsing.pdf'
excerpt: We present a formal analysis of hybrid algorithms in the context of solving mixed-binary quadratic programs (MBQP) via Ising solvers. We leverage copositive optimization and cutting-plane algorithms to derive an algorithm that provable shifts complexity onto the subroutine handled by the Ising solver.
thumbnail: "ccp_icon.png"
---
Recent years have seen significant advances in quantum/quantum-inspired technologies capable ofapproximately searching for the ground state of Ising spin Hamiltonians. The promise of leveraging such technologies to accelerate the solution of difficult optimization problems has spurred an increased interest in exploring methods to integrate Ising problems as part of their solution process, with existing approaches ranging from direct transcription to hybrid quantum-classical approaches rooted in existing optimization algorithms. While it is widely acknowledged that quantum computers should augment classical computers, rather than replace them entirely, comparatively little attention has been directed toward deriving analytical characterizations of their interactions. In this paper, we present a formal analysis of hybrid algorithms in the context of solving mixed-binary quadratic programs (MBQP) via Ising solvers. We show the exactness of a convex copositive reformulation of MBQPs, allowing the resulting reformulation to inherit the straightforward analysis of convex optimization. We propose to solve this reformulation with a hybrid quantum-classical cutting-plane algorithm. Using existing complexity results for convex cutting-plane algorithms, we deduce that the classical portion of this hybrid framework is guaranteed to be polynomial time. This suggests that when applied to NP-hard problems, the complexity of the solution is shifted onto the subroutine handled by the Ising solver.

[paper](http://robinabrown.github.io/files/CopositiveIsing.pdf)

### Bibtex

@article{BrownBernalNeiraEtAl2023,
  author    = {Brown, R. A. and Bernal Neira, D. E. and Venturelli, D. and Pavone, M.},
  title     = {A Copositive Framework for Analysis of Hybrid Ising-classical Algorithms},
  year      = {2023},
  url       = {https://arxiv.org/abs/2207.13630}
}
