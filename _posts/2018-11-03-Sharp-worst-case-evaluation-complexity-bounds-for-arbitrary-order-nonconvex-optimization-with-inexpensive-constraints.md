---
layout: post
title: "Sharp worst-case evaluation complexity bounds for arbitrary-order nonconvex optimization with inexpensive constraints"
date: 2018-11-03 14:04:35
categories: arXiv_AI
tags: arXiv_AI Regularization Optimization
author: Coralia Cartis, Nick I. M. Gould, Philippe L. Toint
mathjax: true
---

* content
{:toc}

##### Abstract
We provide sharp worst-case evaluation complexity bounds for nonconvex minimization problems with general inexpensive constraints, i.e.\ problems where the cost of evaluating/enforcing of the (possibly nonconvex or even disconnected) constraints, if any, is negligible compared to that of evaluating the objective function. These bounds unify, extend or improve all known upper and lower complexity bounds for unconstrained and convexly-constrained problems. It is shown that, given an accuracy level $\epsilon$, a degree of highest available Lipschitz continuous derivatives $p$ and a desired optimality order $q$ between one and $p$, a conceptual regularization algorithm requires no more than $O(\epsilon^{-\frac{p+1}{p-q+1}})$ evaluations of the objective function and its derivatives to compute a suitably approximate $q$-th order minimizer. With an appropriate choice of the regularization, a similar result also holds if the $p$-th derivative is merely H\"older rather than Lipschitz continuous. We provide an example that shows that the above complexity bound is sharp for unconstrained and a wide class of constrained problems, we also give reasons for the optimality of regularization methods from a worst-case complexity point of view, within a large class of algorithms that use the same derivative information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01220](http://arxiv.org/abs/1811.01220)

##### PDF
[http://arxiv.org/pdf/1811.01220](http://arxiv.org/pdf/1811.01220)

