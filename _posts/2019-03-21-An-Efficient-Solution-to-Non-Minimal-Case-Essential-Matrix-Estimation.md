---
layout: post
title: "An Efficient Solution to Non-Minimal Case Essential Matrix Estimation"
date: 2019-03-21 15:47:37
categories: arXiv_CV
tags: arXiv_CV
author: Ji Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Finding relative pose between two calibrated views is a fundamental task in computer vision. Given the minimal number $5$ of required point correspondences, the classical five-point method can be used to calculate the essential matrix. For the non-minimal cases when $N$ ($N &gt; 5$) correct point correspondences are given, which is called $N$-point problem, methods are relatively less mature. In this paper, we solve the $N$-point problem by minimizing the algebraic error and formulate it as a quadratically constrained quadratic program (QCQP). The formulation is based on a simpler parameterization of the feasible region -- the normalized essential matrix manifold -- than previous approaches. Then a globally optimal solution to this problem is obtained by semidefinite relaxation. This allows us to obtain certifiably global solutions to an important non-convex problem in polynomial time. We provide the condition to recover the optimal essential matrix from the relaxed problems. The theoretical guarantees of the semidefinite relaxation are investigated, including the tightness and local stability. Experiments demonstrate that our approach always finds and certifies (a-posteriori) the global optimum of the cost function, and it is dozens of times faster than state-of-the-art globally optimal solutions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09067](http://arxiv.org/abs/1903.09067)

##### PDF
[http://arxiv.org/pdf/1903.09067](http://arxiv.org/pdf/1903.09067)

