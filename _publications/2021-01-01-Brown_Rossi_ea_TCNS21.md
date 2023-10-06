---
title: "On Local Computation for Network-Structured Convex Optimization in Multi-Agent Systems"
collection: publications
permalink: /publication/2021-01-01-Brown_Rossi_ea_TCNS21ß
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2021-01-01
venue: 'IEEE Transactions on Control of Network Systems'
paperurl: 'http://robinabrown.github.io/files/Brown_Rossi_ea_TCNS21.pdf'
---

A number of prototypical optimization problems in multi-agent systems (e.g., task allocation and network load-sharing) exhibit a highly local structure: that is, each agent's decision variables are only directly coupled to few other agent's variables through the objective function or the constraints. In this paper, we develop a rigorous notion of "locality" that quantifies the degree to which agents can compute their portion of the global solution of such a distributed optimization problem based solely on information in their local neighborhood. We build upon the results of Rebeschini and Tatikonda (2019) to develop a more general theory of locality that fully captures the importance of problem data to individual solution components, as opposed to a theory that only captures response to perturbations. This analysis provides a theoretical basis for a rather simple algorithm in which agents individually solve a truncated sub-problem of the global problem, where the size of the sub-problem used depends on the locality of the problem, and the desired accuracy. Numerical results show that the proposed theoretical bounds are remarkably tight for well-conditioned problems

[paper](http://robinabrown.github.io/files/Brown_Rossi_ea_TCNS21.pdf)

### Bibtex

@article{BrownRossiEtAl2021,
  author    = {Brown, R. A. and Rossi, F. and Solovey, K. and Tsao, M. and Wolf, M. T. and Pavone, M.},
  title     = {On Local Computation for Network-Structured Convex Optimization in Multi-Agent Systems},
  journal   = {IEEE Transactions on Control of Network Systems},
  volume    = {8},
  number    = {2},
  pages     = {542-554},
  year      = {2021}
}