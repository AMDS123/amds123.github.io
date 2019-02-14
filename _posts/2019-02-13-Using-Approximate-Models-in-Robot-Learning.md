---
layout: post
title: "Using Approximate Models in Robot Learning"
date: 2019-02-13 01:33:27
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Ali Lenjani
mathjax: true
---

* content
{:toc}

##### Abstract
Trajectory following is one of the complicated control problems when its dynamics are nonlinear, stochastic and include a large number of parameters. The problem has significant difficulties including a large number of trials required for data collection and a massive volume of computations required to find a closed-loop controller for high dimensional and stochastic domains. For solving this type of problem, if we have an appropriate reward function and dynamics model; finding an optimal control policy is possible by using model-based reinforcement learning and optimal control algorithms. However, defining an accurate dynamics model is not possible for complicated problems. Pieter Abbeel and Andrew Ng recently presented an algorithm that requires only an approximate model and only a small number of real-life trials. This algorithm has broad applicability; however, there are some problems regarding the convergence of the algorithm. In this research, required modifications are presented that provide more powerful assurance for converging to optimal control policy. Also updated algorithm is implemented to evaluate the efficiency of the new algorithm by comparing the acquired results with human expert performance. We are using differential dynamic programming (DDP) as the locally trajectory optimizer, and a 2D dynamics and kinematics simulator is used to evaluate the accuracy of the presented algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04696](http://arxiv.org/abs/1902.04696)

##### PDF
[http://arxiv.org/pdf/1902.04696](http://arxiv.org/pdf/1902.04696)

