---
layout: post
title: "DynoPlan: Combining Motion Planning and Deep Neural Network based Controllers for Safe HRL"
date: 2019-06-24 17:34:51
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Daniel Angelov, Yordan Hristov, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Many realistic robotics tasks are best solved compositionally, through control architectures that sequentially invoke primitives and achieve error correction through the use of loops and conditionals taking the system back to alternative earlier states. Recent end-to-end approaches to task learning attempt to directly learn a single controller that solves an entire task, but this has been difficult for complex control tasks that would have otherwise required a diversity of local primitive moves, and the resulting solutions are also not easy to inspect for plan monitoring purposes. In this work, we aim to bridge the gap between hand designed and learned controllers, by representing each as an option in a hybrid hierarchical Reinforcement Learning framework - DynoPlan. We extend the options framework by adding a dynamics model and the use of a nearness-to-goal heuristic, derived from demonstrations. This translates the optimization of a hierarchical policy controller to a problem of planning with a model predictive controller. By unrolling the dynamics of each option and assessing the expected value of each future state, we can create a simple switching controller for choosing the optimal policy within a constrained time horizon similarly to hill climbing heuristic search. The individual dynamics model allows each option to iterate and be activated independently of the specific underlying instantiation, thus allowing for a mix of motion planning and deep neural network based primitives. We can assess the safety regions of the resulting hybrid controller by investigating the initiation sets of the different options, and also by reasoning about the completeness and performance guarantees of the underpinning motion planners.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10099](http://arxiv.org/abs/1906.10099)

##### PDF
[http://arxiv.org/pdf/1906.10099](http://arxiv.org/pdf/1906.10099)

