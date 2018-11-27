---
layout: post
title: "A Differentiable Physics Engine for Deep Learning in Robotics"
date: 2018-11-24 14:41:48
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization Deep_Learning
author: Jonas Degrave, Michiel Hermans, Joni Dambre, Francis wyffels
mathjax: true
---

* content
{:toc}

##### Abstract
An important field in robotics is the optimization of controllers. Currently, robots are often treated as a black box in this optimization process, which is the reason why derivative-free optimization methods such as evolutionary algorithms or reinforcement learning are omnipresent. When gradient-based methods are used, models are kept small or rely on finite difference approximations for the Jacobian. This method quickly grows expensive with increasing numbers of parameters, such as found in deep learning. We propose the implementation of a modern physics engine, which can differentiate control parameters. This engine is implemented for both CPU and GPU. Firstly, this paper shows how such an engine speeds up the optimization process, even for small problems. Furthermore, it explains why this is an alternative approach to deep Q-learning, for using deep learning in robotics. Finally, we argue that this is a big step for deep learning in robotics, as it opens up new possibilities to optimize robots, both in hardware and software.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1611.01652](http://arxiv.org/abs/1611.01652)

##### PDF
[http://arxiv.org/pdf/1611.01652](http://arxiv.org/pdf/1611.01652)

