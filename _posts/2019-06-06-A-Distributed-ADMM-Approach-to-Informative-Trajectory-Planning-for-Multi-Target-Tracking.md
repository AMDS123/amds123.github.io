---
layout: post
title: "A Distributed ADMM Approach to Informative Trajectory Planning for Multi-Target Tracking"
date: 2019-06-06 06:15:48
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Soon-Seo Park, Jung-Su Ha, Doo-Hyun Cho, Han-Lim Choi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a distributed optimization method for informative trajectory planning in multi-target tracking problems. The purpose of such problems is to optimize a sequence of waypoints/control inputs of mobile sensors over a certain future time step to minimize the uncertainty of targets. The planning problem is reformulated as a distributed optimization problem that can be expressed in the form of a subproblem for each target. The subproblems are coupled using the distributed Alternating Direction Method of Multipliers (ADMM). This coupling not only enables the results of each subproblem to be reflected in the optimization process of the other subproblems, but also guides the results of the subproblems to converge to the same solution. In contrast to the existing approaches performing trajectory optimization after assigning tasks, the proposed algorithm does not require the design of a heuristic cost function for task assignment, and it can handle both trajectory optimization and task assignment in multiple target tracking problems simultaneously. In order to reduce the computation time of the algorithm, an edge-cutting method suitable for multiple-target tracking problems is proposed, as is a receding horizon control scheme for real-time implementation, which considers the computation time. Numerical examples are presented to demonstrate the applicability of the algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11068](http://arxiv.org/abs/1807.11068)

##### PDF
[http://arxiv.org/pdf/1807.11068](http://arxiv.org/pdf/1807.11068)

