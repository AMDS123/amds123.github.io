---
layout: post
title: "Safe Feature Elimination for Non-Negativity Constrained Convex Optimization"
date: 2019-07-25 04:24:20
categories: arXiv_CV
tags: arXiv_CV Optimization
author: James Folberth, Stephen Becker
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by recent work on safe feature elimination for $1$-norm regularized least-squares, we develop strategies to eliminate features from convex optimization problems with non-negativity constraints. Our strategy is safe in the sense that it will only remove features/coordinates from the problem when they are guaranteed to be zero at a solution. To perform feature elimination we use an accurate, but not optimal, primal-dual feasible pair, making our methods robust and able to be used on ill-conditioned problems. We supplement our feature elimination problem with a method to construct an accurate dual feasible point from an accurate primal feasible point; this allows us to use a first-order method to find an accurate primal feasible point, then use that point to construct an accurate dual feasible point and perform feature elimination. Under reasonable conditions, our feature elimination strategy will eventually eliminate all zero features from the problem. As an application of our methods we show how safe feature elimination can be used to robustly certify the uniqueness of non-negative least-squares (NNLS) problems. We give numerical examples on a well-conditioned synthetic NNLS problem and a on set of 40000 extremely ill-conditioned NNLS problems arising in a microscopy application.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10831](http://arxiv.org/abs/1907.10831)

##### PDF
[http://arxiv.org/pdf/1907.10831](http://arxiv.org/pdf/1907.10831)

