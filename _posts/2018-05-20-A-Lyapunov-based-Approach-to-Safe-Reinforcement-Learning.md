---
layout: post
title: "A Lyapunov-based Approach to Safe Reinforcement Learning"
date: 2018-05-20 05:12:04
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yinlam Chow, Ofir Nachum, Edgar Duenez-Guzman, Mohammad Ghavamzadeh
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world reinforcement learning (RL) problems, besides optimizing the main objective function, an agent must concurrently avoid violating a number of constraints. In particular, besides optimizing performance it is crucial to guarantee the safety of an agent during training as well as deployment (e.g. a robot should avoid taking actions - exploratory or not - which irrevocably harm its hardware). To incorporate safety in RL, we derive algorithms under the framework of constrained Markov decision problems (CMDPs), an extension of the standard Markov decision problems (MDPs) augmented with constraints on expected cumulative costs. Our approach hinges on a novel \emph{Lyapunov} method. We define and present a method for constructing Lyapunov functions, which provide an effective way to guarantee the global safety of a behavior policy during training via a set of local, linear constraints. Leveraging these theoretical underpinnings, we show how to use the Lyapunov approach to systematically transform dynamic programming (DP) and RL algorithms into their safe counterparts. To illustrate their effectiveness, we evaluate these algorithms in several CMDP planning and decision-making tasks on a safety benchmark domain. Our results show that our proposed method significantly outperforms existing baselines in balancing constraint satisfaction and performance.

##### Abstract (translated by Google)
在许多现实世界的强化学习（RL）问题中，除了优化主要目标函数外，代理还必须同时避免违反许多约束条件。特别是，除了优化性能之外，在培训和部署期间保证代理人的安全是至关重要的（例如，机器人应避免采取行动 - 探索与否 - 这会不可挽回地损害其硬件）。为了将RL纳入安全性，我们在约束马尔可夫决策问题（CMDPs）的框架下推导出算法，这是标准马尔可夫决策问题（MDPs）的扩展，其中增加了对预期累积成本的限制。我们的方法取决于一种新颖的方法。我们定义并提出了一种构造Lyapunov函数的方法，该方法通过一系列局部线性约束条件提供了一种有效的方法来保证训练期间行为策略的全局安全性。利用这些理论基础，我们展示了如何使用Lyapunov方法系统地将动态编程（DP）和RL算法转换为其安全对手。为了说明它们的有效性，我们在安全基准域上的几个CMDP规划和决策任务中评估这些算法。我们的结果表明，我们提出的方法在平衡约束满意度和性能方面明显优于现有基线。

##### URL
[https://arxiv.org/abs/1805.07708](https://arxiv.org/abs/1805.07708)

##### PDF
[https://arxiv.org/pdf/1805.07708](https://arxiv.org/pdf/1805.07708)

