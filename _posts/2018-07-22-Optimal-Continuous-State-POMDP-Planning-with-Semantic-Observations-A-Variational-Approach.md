---
layout: post
title: "Optimal Continuous State POMDP Planning with Semantic Observations: A Variational Approach"
date: 2018-07-22 03:19:41
categories: arXiv_AI
tags: arXiv_AI Relation
author: Luke Burks, Ian Loefgren, Nisar Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
This work develops novel strategies for optimal planning with semantic observations using continuous state Partially Observable Markov Decision Processes (CPOMDPs). Two major innovations are presented in relation to Gaussian mixture (GM) CPOMDP policy approximation methods. While existing methods have many theoretically nice properties, they are hampered by the inability to efficiently represent and reason over hybrid continuous-discrete probabilistic models. The first major innovation is the derivation of closed-form variational Bayes GM approximations of Point-Based Value Iteration Bellman policy backups, using softmax models of continuous-discrete semantic observation probabilities. A key benefit of this approach is that dynamic decision-making tasks can be performed with complex non-Gaussian uncertainties, while also exploiting continuous dynamic state space models (thus avoiding cumbersome and costly discretization). The second major innovation is a new clustering-based technique for mixture condensation that scales well to very large GM policy functions and belief functions. Simulation results for a target search and interception task with semantic observations show that the GM policies resulting from these innovations are more effective than those produced by other state of the art GM and Monte Carlo based policy approximations, but require significantly less modeling overhead and runtime cost. Additional results demonstrate the robustness of this approach to model errors.

##### Abstract (translated by Google)
这项工作利用连续状态部分可观测马尔可夫决策过程（CPOMDP），利用语义观察开发出新的最优规划策略。关于高斯混合（GM）CPOMDP策略近似方法提出了两个主要创新。虽然现有方法具有许多理论上不错的特性，但它们不能有效地表示和推理混合连续离散概率模型。第一个主要创新是使用连续离散语义观测概率的softmax模型推导基于点的值迭代贝尔曼策略备份的闭合变分贝叶斯GM近似。这种方法的一个主要好处是动态决策任务可以用复杂的非高斯不确定性来执行，同时还利用连续动态状态空间模型（从而避免繁琐和昂贵的离散化）。第二个主要创新是基于聚类的新混合物凝结技术，可以很好地扩展到非常大的GM政策功能和信念功能。具有语义观察的目标搜索和拦截任务的仿真结果表明，由这些创新产生的GM策略比其他基于GM和蒙特卡罗的最先进策略近似产生的策略更有效，但需要显着更少的建模开销和运行时成本。其他结果证明了这种方法对模型错误的鲁棒性。

##### URL
[http://arxiv.org/abs/1807.08229](http://arxiv.org/abs/1807.08229)

##### PDF
[http://arxiv.org/pdf/1807.08229](http://arxiv.org/pdf/1807.08229)

