---
layout: post
title: "Multi-objective Bayesian optimisation with preferences over objectives"
date: 2019-02-12 03:47:16
categories: arXiv_AI
tags: arXiv_AI
author: Majid Abdolshah, Alistair Shilton, Santu Rana, Sunil Gupta, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Bayesian multi-objective optimisation algorithm that allows the user to express preference-order constraints on the objectives of the type `objective A is more important than objective B'. Rather than attempting to find a representative subset of the complete Pareto front, our algorithm searches for and returns only those Pareto-optimal points that satisfy these constraints. We formulate a new acquisition function based on expected improvement in dominated hypervolume (EHI) to ensure that the subset of Pareto front satisfying the constraints is thoroughly explored. The hypervolume calculation only includes those points that satisfy the preference-order constraints, where the probability of a point satisfying the constraints is calculated from a gradient Gaussian Process model. We demonstrate our algorithm on both synthetic and real-world problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04228](http://arxiv.org/abs/1902.04228)

##### PDF
[http://arxiv.org/pdf/1902.04228](http://arxiv.org/pdf/1902.04228)

