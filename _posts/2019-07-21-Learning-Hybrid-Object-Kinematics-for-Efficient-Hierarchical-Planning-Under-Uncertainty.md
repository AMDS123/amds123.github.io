---
layout: post
title: "Learning Hybrid Object Kinematics for Efficient Hierarchical Planning Under Uncertainty"
date: 2019-07-21 18:13:52
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Inference
author: Ajinkya Jain, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
Sudden changes in the dynamics of robotic tasks, such as contact with an object or the latching of a door, are often viewed as inconvenient discontinuities that make manipulation difficult. However, when these transitions are well-understood, they can be leveraged to reduce uncertainty or aid manipulation---for example, wiggling a screw to determine if it is fully inserted or not. Current model-free reinforcement learning approaches require large amounts of data to learn to leverage such dynamics, scale poorly as problem complexity grows, and do not transfer well to significantly different problems. By contrast, hierarchical planning-based methods scale well via plan decomposition and work well on a wide variety of problems, but often rely on precise hand-specified models and task decompositions. To combine the advantages of these opposing paradigms, we propose a new method, Act-CHAMP, which (1) learns hybrid kinematics models of objects from unsegmented data, (2) leverages actions, in addition to states, to outperform a state-of-the-art observation-only inference method, and (3) does so in a manner that is compatible with efficient, hierarchical POMDP planning. Beyond simply coping with challenging dynamics, we show that our end-to-end system leverages the learned kinematics to reduce uncertainty, plan efficiently, and use objects in novel ways not encountered during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09014](http://arxiv.org/abs/1907.09014)

##### PDF
[http://arxiv.org/pdf/1907.09014](http://arxiv.org/pdf/1907.09014)

