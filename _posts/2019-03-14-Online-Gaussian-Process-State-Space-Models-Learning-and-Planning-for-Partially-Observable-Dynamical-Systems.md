---
layout: post
title: "Online Gaussian Process State-Space Models: Learning and Planning for Partially Observable Dynamical Systems"
date: 2019-03-14 13:45:58
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization Inference
author: Soon-Seo Park, Young-Jin Park, Han-Lim Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Gaussian process state-space model (GPSSM) is a probabilistic dynamical system that represents unknown transition and/or measurement models as the Gaussian process (GP). The majority of approaches to learning GPSSM are focused on handling given time series data. However, in most dynamical systems, data required for model learning arrives sequentially and accumulates over time. Storing all the data requires large ammounts of memory, and using it for model learning can be computationally infeasible. To overcome this challenge, this paper develops an online inference method for learning the GPSSM (onlineGPSSM) that fuses stochastic variational inference (VI) and online VI. The proposed method can mitigate the computation time issue without catastrophic forgetting and supports adaptation to changes in a system and/or a real environments. Furthermore, we propose a GPSSM-based reinforcement learning (RL) framework for partially observable dynamical systems by combining onlineGPSSM with Bayesian filtering and trajectory optimization algorithms. Numerical examples are presented to demonstrate the applicability of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08643](http://arxiv.org/abs/1903.08643)

##### PDF
[http://arxiv.org/pdf/1903.08643](http://arxiv.org/pdf/1903.08643)

