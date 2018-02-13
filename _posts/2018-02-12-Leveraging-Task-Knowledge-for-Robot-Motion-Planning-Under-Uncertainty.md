---
layout: post
title: "Leveraging Task Knowledge for Robot Motion Planning Under Uncertainty"
date: 2018-02-12 17:47:13
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Ajinkya Jain, Scott Niekum
mathjax: true
---

* content
{:toc}

##### Abstract
Noisy observations coupled with nonlinear dynamics pose one of the biggest challenges in robot motion planning. By decomposing the nonlinear dynamics into a discrete set of local dynamics models, hybrid dynamics provide a natural way to model nonlinear dynamics, especially in systems with sudden "jumps" in the dynamics, due to factors such as contacts. We propose a hierarchical POMDP planner that develops locally optimal motion plans for hybrid dynamics models. The hierarchical planner first develops a high-level motion plan to sequence the local dynamics models to be visited. The high-level plan is then converted into a detailed cost-optimized continuous state plan. This hierarchical planning approach results in a decomposition of the POMDP planning problem into smaller sub-parts that can be solved with significantly lower computational costs. The ability to sequence the visitation of local dynamics models also provides a powerful way to leverage the hybrid dynamics to reduce state uncertainty. We evaluate the proposed planner for two navigation and localization tasks in simulated domains, as well as an assembly task with a real robotic manipulator.

##### Abstract (translated by Google)
噪声观测再加上非线性动力学是机器人运动规划中最大的挑战之一。通过将非线性动力学分解为一组离散的局部动力学模型，混合动力学为模拟非线性动力学提供了一种自然的方法，特别是在动力学中由于诸如接触等因素而突然“跳跃”的系统中。我们提出了一个分层的POMDP规划器，为混合动力学模型开发局部最优运动计划。分级计划员首先制定一个高层次的运动计划，对要访问的局部动态模型进行排序。然后将高层计划转换为详细的成本优化连续状态计划。这种分层规划方法将POMDP规划问题分解为更小的子部分，这些子部分可以用显着更低的计算成本来解决。排序访问局部动力学模型的能力也为利用混合动力学减少状态不确定性提供了强有力的方法。我们评估提议的规划师在模拟领域的两个导航和本地化任务，以及一个真正的机器人操作器的装配任务。

##### URL
[http://arxiv.org/abs/1802.04205](http://arxiv.org/abs/1802.04205)

##### PDF
[http://arxiv.org/pdf/1802.04205](http://arxiv.org/pdf/1802.04205)

