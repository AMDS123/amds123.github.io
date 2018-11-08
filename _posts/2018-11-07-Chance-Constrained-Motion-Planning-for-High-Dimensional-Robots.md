---
layout: post
title: "Chance Constrained Motion Planning for High-Dimensional Robots"
date: 2018-11-07 18:41:59
categories: arXiv_RO
tags: arXiv_RO Sparse Optimization
author: Siyu Dai, Shawn Schaffert, Ashkan Jasour, Andreas Hofmann, Brian Williams
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces Probabilistic Chekov (p-Chekov), a chance-constrained motion planning system that can be applied to high degree-of-freedom (DOF) robots under motion uncertainty and imperfect state information. Given process and observation noise models, it can find feasible trajectories which satisfy a user-specified bound over the probability of collision. Leveraging our previous work in deterministic motion planning which integrated trajectory optimization into a sparse roadmap framework, p-Chekov shows superiority in its planning speed for high-dimensional tasks. P-Chekov incorporates a linear-quadratic Gaussian motion planning approach into the estimation of the robot state probability distribution, applies quadrature theories to waypoint collision risk estimation, and adapts risk allocation approaches to assign allowable probabilities of failure among waypoints. Unlike other existing risk-aware planners, p-Chekov can be applied to high-DOF robotic planning tasks without the convexification of the environment. The experiment results in this paper show that this p-Chekov system can effectively reduce collision risk and satisfy user-specified chance constraints in typical real-world planning scenarios for high-DOF robots.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03073](http://arxiv.org/abs/1811.03073)

##### PDF
[http://arxiv.org/pdf/1811.03073](http://arxiv.org/pdf/1811.03073)

