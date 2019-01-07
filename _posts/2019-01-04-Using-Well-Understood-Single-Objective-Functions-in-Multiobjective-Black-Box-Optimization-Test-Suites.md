---
layout: post
title: "Using Well-Understood Single-Objective Functions in Multiobjective Black-Box Optimization Test Suites"
date: 2019-01-04 09:47:43
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Dimo Brockhoff (RANDOPT), Tea Tusar, Anne Auger (RANDOPT), Nikolaus Hansen (RANDOPT)
mathjax: true
---

* content
{:toc}

##### Abstract
Several test function suites are being used for numerical benchmarking of multiobjective optimization algorithms. While they have some desirable properties, like well-understood Pareto sets and Pareto fronts of various shapes, most of the currently used functions possess characteristics that are arguably under-represented in real-world problems. They mainly stem from the easier construction of such functions and result in improbable properties such as separability, optima located exactly at the boundary constraints, and the existence of variables that solely control the distance between a solution and the Pareto front. Here, we propose an alternative way to constructing multiobjective problems-by combining existing single-objective problems from the literature. We describe in particular the bbob-biobj test suite with 55 bi-objective functions in continuous domain, and its extended version with 92 bi-objective functions (bbob-biobj-ext). Both test suites have been implemented in the COCO platform for black-box optimization benchmarking. Finally, we recommend a general procedure for creating test suites for an arbitrary number of objectives. Besides providing the formal function definitions and presenting their (known) properties, this paper also aims at giving the rationale behind our approach in terms of groups of functions with similar properties, objective space normalization, and problem instances. The latter allows us to easily compare the performance of deterministic and stochastic solvers, which is an often overlooked issue in benchmarking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1604.00359](http://arxiv.org/abs/1604.00359)

##### PDF
[http://arxiv.org/pdf/1604.00359](http://arxiv.org/pdf/1604.00359)

