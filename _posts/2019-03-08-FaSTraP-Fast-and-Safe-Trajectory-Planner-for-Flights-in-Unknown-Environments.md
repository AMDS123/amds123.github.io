---
layout: post
title: "FaSTraP: Fast and Safe Trajectory Planner for Flights in Unknown Environments"
date: 2019-03-08 17:04:06
categories: arXiv_RO
tags: arXiv_RO Knowledge Optimization
author: Jesus Tordesillas, Brett T. Lopez, Jonathan P. How
mathjax: true
---

* content
{:toc}

##### Abstract
Planning high-speed trajectories for UAVs in unknown environments requires extremely fast algorithms able to solve the trajectory generation problem in real-time in order to be able to react quickly to the changing knowledge of the world, but that guarantee safety at all times. The desire of maintaining computational tractability typically leads to optimization problems that do not include the obstacles (collision checks are done on the solutions) or to formulations that use a convex decomposition of the free space and then impose an ad hoc allocation of each interval of the trajectory in a specific polyhedron. Moreover, safety guarantees are usually obtained by having a local planner that plans a trajectory with a final "stop" condition in the free-known space. However, these two decisions typically lead to slow and conservative trajectories. We propose FaSTrap (Fast and Safe Trajectory Planner) to overcome these issues. FasTrap obtains faster trajectories by enabling the local planner to optimize in both free-known and unknown spaces. Safety guarantees are ensured by always having a feasible, safe back-up trajectory in the free-known space at the start of each replanning step. Furthermore, we present a Mixed Integer Quadratic Problem (MIQP) formulation in which the solver can choose the interval allocation and where a heuristics for the time allocation is computed efficiently using the result of the previous replanning iteration. This proposed algorithm is tested both in simulation and in real hardware, showing agile flights in unknown cluttered environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03558](http://arxiv.org/abs/1903.03558)

##### PDF
[http://arxiv.org/pdf/1903.03558](http://arxiv.org/pdf/1903.03558)

