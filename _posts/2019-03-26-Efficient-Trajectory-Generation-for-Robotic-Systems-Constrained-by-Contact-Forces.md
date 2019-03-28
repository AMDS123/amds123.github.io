---
layout: post
title: "Efficient Trajectory Generation for Robotic Systems Constrained by Contact Forces"
date: 2019-03-26 21:40:46
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Jaemin Lee, Efstathios Bakolas, Luis Sentis
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a trajectory generation method for robotic systems with contact force constraint based on optimal control and reachability analysis. Normally, the dynamics and constraints of the contact-constrained robot are nonlinear and coupled to each other. Instead of linearizing the model and constraints, we directly solve the optimal control problem to obtain the feasible state trajectory and the control input of the system. A tractable optimal control problem is formulated which is addressed by dual approaches, which are sampling-based dynamic programming and rigorous reachability analysis. The sampling-based method and Partially Observable Markov Decision Process (POMDP) are used to break down the end-to-end trajectory generation problem via sample-wise optimization in terms of given conditions. The result generates sequential pairs of subregions to be passed to reach the final goal. The reachability analysis ensures that we will find at least one trajectory starting from a given initial state and going through a sequence of subregions. The distinctive contributions of our method are to enable handling the intricate contact constraint coupled with system's dynamics due to the reduction of computational complexity of the algorithm. We validate our method using extensive numerical simulations with a legged robot.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11163](http://arxiv.org/abs/1903.11163)

##### PDF
[http://arxiv.org/pdf/1903.11163](http://arxiv.org/pdf/1903.11163)

