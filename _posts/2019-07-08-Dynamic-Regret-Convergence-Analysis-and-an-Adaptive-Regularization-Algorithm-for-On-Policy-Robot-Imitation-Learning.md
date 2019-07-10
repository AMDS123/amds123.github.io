---
layout: post
title: "Dynamic Regret Convergence Analysis and an Adaptive Regularization Algorithm for On-Policy Robot Imitation Learning"
date: 2019-07-08 23:07:13
categories: arXiv_RO
tags: arXiv_RO Regularization Knowledge Optimization
author: Jonathan N. Lee, Michael Laskey, Ajay Kumar Tanwani, Anil Aswani, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
On-policy imitation learning algorithms such as DAgger evolve a robot control policy by executing it, measuring performance (loss), obtaining corrective feedback from a supervisor, and generating the next policy. As the loss between iterations can vary unpredictably, a fundamental question is under what conditions this process will eventually achieve a converged policy. If one assumes the underlying trajectory distribution is static (stationary), it is possible to prove convergence for DAgger. However, in more realistic models for robotics, the underlying trajectory distribution is dynamic because it is a function of the policy. Recent results show it is possible to prove convergence of DAgger when a regularity condition on the rate of change of the trajectory distributions is satisfied. In this article, we reframe this result using dynamic regret theory from the field of online optimization and show that dynamic regret can be applied to any on-policy algorithm to analyze its convergence and optimality. These results inspire a new algorithm, Adaptive On-Policy Regularization (AOR), that ensures the conditions for convergence. We present simulation results with cart-pole balancing and locomotion benchmarks that suggest AOR can significantly decrease dynamic regret and chattering as the robot learns. To our knowledge, this the first application of dynamic regret theory to imitation learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02184](http://arxiv.org/abs/1811.02184)

##### PDF
[http://arxiv.org/pdf/1811.02184](http://arxiv.org/pdf/1811.02184)

