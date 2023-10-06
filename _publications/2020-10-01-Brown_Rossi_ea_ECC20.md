---
title: "Exploiting Locality and Structure for Distributed Optimization in Multi-Agent Systems"
collection: publications
permalink: /publication/2009-10-01-Brown_Rossi_ea_ECC20
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-05-01
venue: 'European Control Conference'
paperurl: 'http://robinabrown.github.io/files/Brown_Rossi_ea_ECC20.pdf'
citation: ' R. A. Brown, F. Rossi, K. Solovey, M. T. Wolf, and M. Pavone, “Exploiting Locality and Structure for Distributed Optimization in Multi-Agent Systems,” in European Control Conference, St. Petersburg, Russia, 2020'
---
A number of prototypical optimization problems in multi-agent systems (e.g. task allocation and network load-sharing) exhibit a highly local structure: that is, each agent's decision variables are only directly coupled to few other agent's variables through the objective function or the constraints. Nevertheless, existing algorithms for distributed optimization generally do not exploit the locality structure of the problem, requiring all agents to compute or exchange the full set of decision variables. In this paper, we develop a rigorous notion of "locality" that relates the structural properties of a linearly-constrained convex optimization problem (in particular, the sparsity structure of the constraint matrix and the objective function) to the amount of information that agents should exchange to compute an arbitrarily high-quality approximation to the problem from a cold-start. We leverage the notion of locality to develop a locality-aware distributed optimization algorithm, and we show that, for problems where individual agents only require to know a small portion of the optimal solution, the algorithm requires very limited inter-agent communication. Numerical results show that the convergence rate of our algorithm is directly explained by the locality parameter proposed, and that the proposed theoretical bounds are remarkably tight.

[paper](http://robinabrown.github.io/files/Brown_Rossi_ea_ECC20.pdf)

### Bibtex

@inproceedings{BrownRossiEtAl20,
  author    = {Brown, R. A. and Rossi, F. and Solovey, K. and Wolf, M. T. and Pavone, M.},
  title     = {Exploiting Locality and Structure for Distributed Optimization in Multi-Agent Systems},
  booktitle = {European Control Conference},
  year      = {2020},
  address   = {St. Petersburg, Russia}
}