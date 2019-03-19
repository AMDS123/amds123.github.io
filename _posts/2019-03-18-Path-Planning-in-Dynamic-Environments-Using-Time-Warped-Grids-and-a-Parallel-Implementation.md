---
layout: post
title: "Path Planning in Dynamic Environments Using Time-Warped Grids and a Parallel Implementation"
date: 2019-03-18 13:48:17
categories: arXiv_RO
tags: arXiv_RO
author: Siavash Farzan, Guilherme N. DeSouza
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a solution to the problem of smooth path planning for mobile robots in dynamic and unknown environments. A novel concept of Time-Warped Grid is introduced to predict the pose of obstacles in the environment and avoid collisions. The algorithm is implemented using C/C++ and the CUDA programming environment, and combines stochastic estimation (Kalman filter), harmonic potential fields and a rubber band model, and it translates naturally into the parallel paradigm of GPU programming. In simple terms, time-warped grids are progressively wider orbits around the mobile robot. Those orbits represent the variable time intervals estimated by the robot to reach detected obstacles. The proposed method was tested using several simulation scenarios for the Pioneer P3-DX robot, which demonstrated the robustness of the algorithm by finding the optimum path in terms of smoothness, distance, and collision-free, in both static or dynamic environments, and with large number of obstacles.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07441](http://arxiv.org/abs/1903.07441)

##### PDF
[http://arxiv.org/pdf/1903.07441](http://arxiv.org/pdf/1903.07441)

