---
layout: post
title: "Log-barrier constrained CNNs"
date: 2019-04-08 17:25:46
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Optimization
author: Hoel Kervadec, Jose Dolz, Jing Yuan, Christian Desrosiers, Eric Granger, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
This study investigates imposing inequality constraints on the outputs of CNNs for weakly supervised segmentation. In the general context of deep networks, constraints are commonly handled with penalty approaches for their simplicity, and despite their well-known limitations. Lagrangian optimization has well-established theoretical and practical advantages over penalty methods, but has been largely avoided for deep CNNs, mainly due to computational complexity and stability/convergence issues caused by alternating stochastic optimization and dual updates. Several recent studies showed that, in the context of deep CNNs, the theoretical advantages of Lagrangian optimization over simple penalties do not materialize in practice, with performances that are, surprisingly, worse. 
 We leverage well-established concepts in interior-point methods, which approximate Lagrangian optimization with a sequence of unconstrained problems, while completely avoiding dual steps/projections. Specifically, we propose a sequence of unconstrained {\em log-barrier-extension} losses for approximating inequality-constrained CNN problems. The proposed extension has a duality-gap bound, which yields sub-optimality certificates for feasible solutions in the case of convex losses. While sub-optimality is not guaranteed for non-convex problems, the result shows that log-barrier extensions are a principled way to approximate Lagrangian optimization for constrained CNNs. Our approach addresses the well-known limitations of penalty methods and, at the same time, removes the explicit dual steps of Lagrangian optimization. We report comprehensive experiments showing that our formulation outperforms a recent penalty-based constrained CNN method, both in terms of accuracy and training stability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04205](http://arxiv.org/abs/1904.04205)

##### PDF
[http://arxiv.org/pdf/1904.04205](http://arxiv.org/pdf/1904.04205)

