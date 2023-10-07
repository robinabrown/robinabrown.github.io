---
title: "A Unified View of SDP-based Neural Network Verification through Completely Positive Programming"
collection: publications
permalink: /publication/UnifiedSDPVerification
date: 2022-03-01
venue: 'Int. Conf. on Artificial Intelligence and Statistics'
paperurl: 'http://robinabrown.github.io/files/UnifiedSDPVerification.pdf'
excerpt: We unify several SDP relaxations for ReLU neural network verification by providing an exact convex formulation as a completely-positive program. This provides a path for relaxations that systematically trade off tightness and efficiency.
thumbnail: "verification_icon.png"
---
Verifying that input-output relationships of a neural network conform to prescribed operational specifications is a key enabler towards deploying these networks in safety-critical applications. Semidefinite programming (SDP)-based approaches to Rectified Linear Unit (ReLU) network verification transcribe this problem into an optimization problem, where the accuracy of any such formulation reflects the level of fidelity in how the neural network computation is represented, as well as the relaxations of intractable constraints. While the literature contains much progress on improving the tightness of SDP formulations while maintaining tractability, comparatively little work has been devoted to the other extreme, i.e., how to most accurately capture the original verification problem before SDP relaxation. In this work, we develop an exact, convex formulation of verification as a completely positive program (CPP), and provide analysis showing that our formulation is minimal---the removal of any constraint fundamentally misrepresents the neural network computation. We leverage our formulation to provide a unifying view of existing approaches, and give insight into the source of large relaxation gaps observed in some cases.

[paper](http://robinabrown.github.io/files/UnifiedSDPVerification.pdf)

### Bibtex
@inproceedings{BrownSchmerlingEtAl2022,
  author    = {Brown, R. and Schmerling, E. and Azizan, N. and Pavone, M.},
  title     = {A Unified View of SDP-based Neural Network Verification through Completely Positive Programming},
  booktitle = {Int. Conf. on Artificial Intelligence and Statistics},
  year      = {2022}
}