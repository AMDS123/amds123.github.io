---
layout: post
title: "Robustness of accelerated first-order algorithms for strongly convex optimization problems"
date: 2019-05-27 07:19:13
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Hesameddin Mohammadi, Meisam Razaviyayn, Mihailo R. Jovanovi&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
We study the robustness of accelerated first-order algorithms to stochastic uncertainties in gradient evaluation. Specifically, for unconstrained, smooth, strongly convex optimization problems, we examine the mean-square error in the optimization variable when the iterates are perturbed by additive white noise. This type of uncertainty may arise in situations where an approximation of the gradient is sought through measurements of a real system or in a distributed computation over network. Even though the underlying dynamics of first-order algorithms for this class of problems are nonlinear, we establish upper bounds on the mean-square deviation from the optimal value that are tight up to constant factors. Our analysis quantifies fundamental trade-offs between noise amplification and convergence rates obtained via any acceleration scheme similar to Nesterov's or heavy-ball methods. To gain additional analytical insight, for strongly convex quadratic problems we explicitly evaluate the steady-state variance of the optimization variable in terms of the eigenvalues of the Hessian of the objective function. We demonstrate that the entire spectrum of the Hessian, rather than just the extreme eigenvalues, influence robustness of noisy algorithms. We specialize this result to the problem of distributed averaging over undirected networks and examine the role of network size and topology on the robustness of noisy accelerated algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.11011](http://arxiv.org/abs/1905.11011)

##### PDF
[http://arxiv.org/pdf/1905.11011](http://arxiv.org/pdf/1905.11011)

