---
layout: post
title: "Robust Tracking with Model Mismatch for Fast and Safe Planning: an SOS Optimization Approach"
date: 2019-07-23 20:01:06
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Sumeet Singh, Mo Chen, Sylvia L. Herbert, Claire J. Tomlin, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
In the pursuit of real-time motion planning, a commonly adopted practice is to compute a trajectory by running a planning algorithm on a simplified, low-dimensional dynamical model, and then employ a feedback tracking controller that tracks such a trajectory by accounting for the full, high-dimensional system dynamics. While this strategy of planning with model mismatch generally yields fast computation times, there are no guarantees of dynamic feasibility, which hampers application to safety-critical systems. Building upon recent work that addressed this problem through the lens of Hamilton-Jacobi (HJ) reachability, we devise an algorithmic framework whereby one computes, offline, for a pair of "planner" (i.e., low-dimensional) and "tracking" (i.e., high-dimensional) models, a feedback tracking controller and associated tracking bound. This bound is then used as a safety margin when generating motion plans via the low-dimensional model. Specifically, we harness the computational tool of sum-of-squares (SOS) programming to design a bilinear optimization algorithm for the computation of the feedback tracking controller and associated tracking bound. The algorithm is demonstrated via numerical experiments, with an emphasis on investigating the trade-off between the increased computational scalability afforded by SOS and its intrinsic conservativeness. Collectively, our results enable scaling the appealing strategy of planning with model mismatch to systems that are beyond the reach of HJ analysis, while maintaining safety guarantees.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.00649](http://arxiv.org/abs/1808.00649)

##### PDF
[http://arxiv.org/pdf/1808.00649](http://arxiv.org/pdf/1808.00649)

