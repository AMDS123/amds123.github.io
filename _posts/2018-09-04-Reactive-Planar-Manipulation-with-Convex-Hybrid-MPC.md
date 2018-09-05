---
layout: post
title: "Reactive Planar Manipulation with Convex Hybrid MPC"
date: 2018-09-04 14:01:33
categories: arXiv_RO
tags: arXiv_RO Tracking Optimization
author: Francois Robert Hogan, Eudald Romo Grau, Alberto Rodriguez
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a reactive controller for planar manipulation tasks that leverages machine learning to achieve real-time performance. The approach is based on a Model Predictive Control (MPC) formulation, where the goal is to find an optimal sequence of robot motions to achieve a desired object motion. Due to the multiple contact modes associated with frictional interactions, the resulting optimization program suffers from combinatorial complexity when tasked with determining the optimal sequence of modes. 
 To overcome this difficulty, we formulate the search for the optimal mode sequences offline, separately from the search for optimal control inputs online. Using tools from machine learning, this leads to a convex hybrid MPC program that can be solved in real-time. We validate our algorithm on a planar manipulation experimental setup where results show that the convex hybrid MPC formulation with learned modes achieves good closed-loop performance on a trajectory tracking problem.

##### Abstract (translated by Google)
本文介绍了一种用于平面操纵任务的反应式控制器，它利用机器学习来实现实时性能。该方法基于模型预测控制（MPC）公式，其目标是找到最佳的机器人运动序列以实现期望的对象运动。由于与摩擦相互作用相关联的多种接触模式，当确定最佳模式序列时，所得到的优化程序遭受组合复杂性的影响。
 为了克服这个困难，我们离线搜索最佳模式序列，与在线搜索最佳控制输入分开。使用机器学习中的工具，可以实现可以实时求解的凸混合MPC程序。我们在平面操纵实验装置上验证了我们的算法，其结果表明具有学习模式的凸混合MPC公式在轨迹跟踪问题上实现了良好的闭环性能。

##### URL
[http://arxiv.org/abs/1710.05724](http://arxiv.org/abs/1710.05724)

##### PDF
[http://arxiv.org/pdf/1710.05724](http://arxiv.org/pdf/1710.05724)

