---
layout: post
title: "A novel model-based heuristic for energy optimal motion planning for automated driving"
date: 2018-03-08 09:39:34
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Zlatan Ajanovic, Michael Stolz, Martin Horn
mathjax: true
---

* content
{:toc}

##### Abstract
Predictive motion planning is the key to achieve energy-efficient driving, which is one of the main benefits of automated driving. Researchers have been studying the planning of velocity trajectories, a simpler form of motion planning, for over a decade now and many different methods are available. Dynamic programming has shown to be the most common choice due to its numerical background and ability to include nonlinear constraints and models. Although planning of an optimal trajectory is done in a systematic way, dynamic programming does not use any knowledge about the considered problem to guide the exploration and therefore explores all possible trajectories. 
 A* is a search algorithm which enables using knowledge about the problem to guide the exploration to the most promising solutions first. Knowledge has to be represented in a form of a heuristic function, which gives an optimistic estimate of cost for transitioning to the final state, which is not a straightforward task. This paper presents a novel heuristics incorporating air drag and auxiliary power as well as operational costs of the vehicle, besides kinetic and potential energy and rolling resistance known in the literature. Furthermore, optimal cruising velocity, which depends on vehicle aerodynamic properties and auxiliary power, is derived. Results are compared for different variants of heuristic functions and dynamic programming as well.

##### Abstract (translated by Google)
预测性运动计划是实现节能驾驶的关键，这是自动驾驶的主要优势之一。研究人员一直在研究速度轨迹的规划，这是一种更简单的运动规划形式，现在已有十多年了，并且有许多不同的方法可用。由于其数值背景和包含非线性约束和模型的能力，动态规划已被证明是最常见的选择。尽管最佳轨迹的规划是以系统的方式完成的，但动态规划并不使用关于所考虑问题的任何知识来指导勘探并因此探索所有可能的轨迹。
 A *是一种搜索算法，它可以使用关于问题的知识来指导探索首先找到最有前途的解决方案。知识必须以启发式函数的形式来表示，这对于过渡到最终状态的成本给出乐观的估计，这不是一个简单的任务。除了文献中已知的动能和势能以及滚动阻力之外，本文提出了一种新型的启发式方法，其结合了空气阻力和辅助动力以及车辆的运行成本。此外，导出了取决于车辆空气动力特性和辅助动力的最佳巡航速度。对启发式函数和动态编程的不同变体的结果进行比较。

##### URL
[http://arxiv.org/abs/1712.03719](http://arxiv.org/abs/1712.03719)

##### PDF
[http://arxiv.org/pdf/1712.03719](http://arxiv.org/pdf/1712.03719)

