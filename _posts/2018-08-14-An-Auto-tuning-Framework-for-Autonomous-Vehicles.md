---
layout: post
title: "An Auto-tuning Framework for Autonomous Vehicles"
date: 2018-08-14 22:20:09
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Haoyang Fan, Zhongpu Xia, Changchun Liu, Yaqin Chen, Qi Kong
mathjax: true
---

* content
{:toc}

##### Abstract
Many autonomous driving motion planners generate trajectories by optimizing a reward/cost functional. Designing and tuning a high-performance reward/cost functional for Level-4 autonomous driving vehicles with exposure to different driving conditions is challenging. Traditionally, reward/cost functional tuning involves substantial human effort and time spent on both simulations and road tests. As the scenario becomes more complicated, tuning to improve the motion planner performance becomes increasingly difficult. To systematically solve this issue, we develop a data-driven auto-tuning framework based on the Apollo autonomous driving framework. The framework includes a novel rank-based conditional inverse reinforcement learning algorithm, an offline training strategy and an automatic method of collecting and labeling data. Our auto-tuning framework has the following advantages that make it suitable for tuning an autonomous driving motion planner. First, compared to that of most inverse reinforcement learning algorithms, our algorithm training is efficient and capable of being applied to different scenarios. Second, the offline training strategy offers a safe way to adjust the parameters before public road testing. Third, the expert driving data and information about the surrounding environment are collected and automatically labeled, which considerably reduces the manual effort. Finally, the motion planner tuned by the framework is examined via both simulation and public road testing and is shown to achieve good performance.

##### Abstract (translated by Google)
许多自动驾驶运动规划器通过优化奖励/成本功能来产生轨迹。为暴露于不同驾驶条件的Level-4自动驾驶车辆设计和调整高性能奖励/成本功能具有挑战性。传统上，奖励/成本功能调整涉及大量的人力和在模拟和道路测试上花费的时间。随着场景变得更加复杂，调整以改善运动规划器性能变得越来越困难。为了系统地解决这个问题，我们开发了一个基于Apollo自动驾驶框架的数据驱动自动调整框架。该框架包括一种新颖的基于秩的条件逆强化学习算法，离线训练策略以及收集和标记数据的自动方法。我们的自动调整框架具有以下优点，使其适用于调整自动驾驶运动规划器。首先，与大多数逆强化学习算法相比，我们的算法训练是有效的，能够应用于不同的场景。其次，离线培训策略提供了一种在公共道路测试之前调整参数的安全方法。第三，收集并自动标记专家驾驶数据和关于周围环境的信息，这大大减少了手动操作。最后，通过模拟和公共道路测试检查由框架调整的运动规划器，并显示出实现良好的性能。

##### URL
[http://arxiv.org/abs/1808.04913](http://arxiv.org/abs/1808.04913)

##### PDF
[http://arxiv.org/pdf/1808.04913](http://arxiv.org/pdf/1808.04913)

