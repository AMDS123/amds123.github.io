---
layout: post
title: "Verifying Controllers Against Adversarial Examples with Bayesian Optimization"
date: 2018-02-26 11:03:21
categories: arXiv_RO
tags: arXiv_RO Adversarial Reinforcement_Learning Optimization
author: Shromona Ghosh, Felix Berkenkamp, Gireeja Ranade, Shaz Qadeer, Ashish Kapoor
mathjax: true
---

* content
{:toc}

##### Abstract
Recent successes in reinforcement learning have lead to the development of complex controllers for real-world robots. As these robots are deployed in safety-critical applications and interact with humans, it becomes critical to ensure safety in order to avoid causing harm. A first step in this direction is to test the controllers in simulation. To be able to do this, we need to capture what we mean by safety and then efficiently search the space of all behaviors to see if they are safe. In this paper, we present an active-testing framework based on Bayesian Optimization. We specify safety constraints using logic and exploit structure in the problem in order to test the system for adversarial counter examples that violate the safety specifications. These specifications are defined as complex boolean combinations of smooth functions on the trajectories and, unlike reward functions in reinforcement learning, are expressive and impose hard constraints on the system. In our framework, we exploit regularity assumptions on individual functions in form of a Gaussian Process (GP) prior. We combine these into a coherent optimization framework using problem structure. The resulting algorithm is able to provably verify complex safety specifications or alternatively find counter examples. Experimental results show that the proposed method is able to find adversarial examples quickly.

##### Abstract (translated by Google)
最近在强化学习方面取得的成功导致了现实世界机器人复杂控制器的发展。由于这些机器人部署在对安全至关重要的应用中并与人类互动，因此确保安全以避免造成伤害变得至关重要。这个方向的第一步是在模拟中测试控制器。为了做到这一点，我们需要捕捉我们的安全意义，然后有效地搜索所有行为的空间，看看它们是否安全。在本文中，我们提出了一个基于贝叶斯优化的主动测试框架。我们使用逻辑来指定安全约束并利用问题的结构来测试系统是否存在违反安全规范的敌对计数器示例。这些规范被定义为轨迹上平滑函数的复杂布尔组合，并且与强化学习中的奖励函数不同，它们具有表达力并对系统施加了严格的限制。在我们的框架中，我们利用高斯过程（GP）之前的单个函数的规则性假设。我们将这些组合成一个使用问题结构的一致性优化框架。由此产生的算法能够证明复杂的安全规范，或者找到反例。实验结果表明，该方法能够快速找到对手的例子。

##### URL
[http://arxiv.org/abs/1802.08678](http://arxiv.org/abs/1802.08678)

##### PDF
[http://arxiv.org/pdf/1802.08678](http://arxiv.org/pdf/1802.08678)

