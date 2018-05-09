---
layout: post
title: "Fast Model Identification via Physics Engines for Data-Efficient Policy Search"
date: 2018-05-07 19:45:10
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Shaojun Zhu, Andrew Kimmel, Kostas E. Bekris, Abdeslam Boularias
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for identifying mechanical parameters of robots or objects, such as their mass and friction coefficients. Key features are the use of off-the-shelf physics engines and the adaptation of a Bayesian optimization technique towards minimizing the number of real-world experiments needed for model-based reinforcement learning. The proposed framework reproduces in a physics engine experiments performed on a real robot and optimizes the model's mechanical parameters so as to match real-world trajectories. The optimized model is then used for learning a policy in simulation, before real-world deployment. It is well understood, however, that it is hard to exactly reproduce real trajectories in simulation. Moreover, a near-optimal policy can be frequently found with an imperfect model. Therefore, this work proposes a strategy for identifying a model that is just good enough to approximate the value of a locally optimal policy with a certain confidence, instead of wasting effort on identifying the most accurate model. Evaluations, performed both in simulation and on a real robotic manipulation task, indicate that the proposed strategy results in an overall time-efficient, integrated model identification and learning solution, which significantly improves the data-efficiency of existing policy search algorithms.

##### Abstract (translated by Google)
本文提出了一种用于识别机器人或物体的机械参数的方法，例如其质量和摩擦系数。主要功能是使用现成的物理引擎，并采用贝叶斯优化技术来最小化基于模型的强化学习所需的实际实验数量。所提出的框架在物理引擎中再现了在真实机器人上执行的实验并且优化了模型的机械参数以匹配真实世界的轨迹。在实际部署之前，优化后的模型将用于学习仿真策略。然而，人们很好理解，在模拟中很难准确再现真实的轨迹。此外，通过不完善的模型可以经常发现近乎最优的策略。因此，这项工作提出了一种策略，用于确定一个模型，该模型足以以一定的信心逼近具有局部最优策略的价值，而不是浪费精力来识别最准确的模型。在模拟和真实机器人操作任务中执行的评估表明，所提出的策略产生了总体时间效率高，集成的模型识别和学习解决方案，其显着提高了现有策略搜索算法的数据效率。

##### URL
[http://arxiv.org/abs/1710.08893](http://arxiv.org/abs/1710.08893)

##### PDF
[http://arxiv.org/pdf/1710.08893](http://arxiv.org/pdf/1710.08893)

