---
layout: post
title: "Policy Optimization via Importance Sampling"
date: 2018-09-17 09:42:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Alberto Maria Metelli, Matteo Papini, Francesco Faccio, Marcello Restelli
mathjax: true
---

* content
{:toc}

##### Abstract
Policy optimization is an effective reinforcement learning approach to solve continuous control tasks. Recent achievements have shown that alternating on-line and off-line optimization is a successful choice for efficient trajectory reuse. However, deciding when to stop optimizing and collect new trajectories is non-trivial as it requires to account for the variance of the objective function estimate. In this paper, we propose a novel model-free policy search algorithm, POIS, applicable in both control-based and parameter-based settings. We first derive a high-confidence bound for importance sampling estimation and then we define a surrogate objective function which is optimized off-line using a batch of trajectories. Finally, the algorithm is tested on a selection of continuous control tasks, with both linear and deep policies, and compared with the state-of-the-art policy optimization methods.

##### Abstract (translated by Google)
策略优化是解决连续控制任务的有效强化学习方法。最近的成就表明，交替的在线和离线优化是有效轨迹重用的成功选择。然而，决定何时停止优化和收集新轨迹是非平凡的，因为它需要考虑目标函数估计的方差。在本文中，我们提出了一种新的无模型策略搜索算法POIS，适用于基于控制和基于参数的设置。我们首先得出重要性抽样估计的高置信度界限，然后我们定义一个替代目标函数，该函数使用一批轨迹离线优化。最后，该算法在一系列连续控制任务上进行测试，包括线性和深度策略，并与最先进的策略优化方法进行比较。

##### URL
[http://arxiv.org/abs/1809.06098](http://arxiv.org/abs/1809.06098)

##### PDF
[http://arxiv.org/pdf/1809.06098](http://arxiv.org/pdf/1809.06098)

