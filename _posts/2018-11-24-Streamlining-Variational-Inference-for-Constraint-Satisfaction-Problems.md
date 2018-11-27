---
layout: post
title: "Streamlining Variational Inference for Constraint Satisfaction Problems"
date: 2018-11-24 11:08:14
categories: arXiv_AI
tags: arXiv_AI Survey Inference
author: Aditya Grover, Tudor Achim, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
Several algorithms for solving constraint satisfaction problems are based on survey propagation, a variational inference scheme used to obtain approximate marginal probability estimates for variable assignments. These marginals correspond to how frequently each variable is set to true among satisfying assignments, and are used to inform branching decisions during search; however, marginal estimates obtained via survey propagation are approximate and can be self-contradictory. We introduce a more general branching strategy based on streamlining constraints, which sidestep hard assignments to variables. We show that streamlined solvers consistently outperform decimation-based solvers on random k-SAT instances for several problem sizes, shrinking the gap between empirical performance and theoretical limits of satisfiability by 16.3% on average for k=3,4,5,6.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09813](https://arxiv.org/abs/1811.09813)

##### PDF
[https://arxiv.org/pdf/1811.09813](https://arxiv.org/pdf/1811.09813)

