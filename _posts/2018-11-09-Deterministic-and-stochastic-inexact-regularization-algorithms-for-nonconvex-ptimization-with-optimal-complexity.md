---
layout: post
title: "Deterministic and stochastic inexact regularization algorithms for nonconvex ptimization with optimal complexity"
date: 2018-11-09 09:39:53
categories: arXiv_AI
tags: arXiv_AI Regularization
author: S. Bellavia, G. Gurioli, B. Morini, Ph.L. Toint
mathjax: true
---

* content
{:toc}

##### Abstract
A regularization algorithm using inexact function values and inexact derivatives is proposed and its evaluation complexity analyzed. This algorithm is applicable to unconstrained problems and to problems with inexpensive constraints (that is constraints whose evaluation and enforcement has negligible cost) under the assumption that the derivative of highest degree is $\beta$-H\"{o}lder continuous. It features a very flexible adaptive mechanism for determining the inexactness which is allowed, at each iteration, when computing objective function values and derivatives. The complexity analysis covers arbitrary optimality order and arbitrary degree of available approximate derivatives. It extends results of Cartis, Gould and Toint (2018) on the evaluation complexity to the inexact case: if a $q$th order minimizer is sought using approximations to the first $p$ derivatives, it is proved that a suitable approximate minimizer within $\epsilon$ is computed by the proposed algorithm in at most $O(\epsilon^{-\frac{p+\beta}{p-q+\beta}})$ iterations and at most $O(|\log(\epsilon)|\epsilon^{-\frac{p+\beta}{p-q+\beta}})$ approximate evaluations. While the proposed framework remains so far conceptual for high degrees and orders, it is shown to yield simple and computationally realistic inexact methods when specialized to the unconstrained and bound-constrained first- and second-order cases. The deterministic complexity results are finally extended to the stochastic context, yielding adaptive sample-size rules for subsampling methods typical of machine learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03831](http://arxiv.org/abs/1811.03831)

##### PDF
[http://arxiv.org/pdf/1811.03831](http://arxiv.org/pdf/1811.03831)

