---
layout: post
title: "LVIS: Learning from Value Function Intervals for Contact-Aware Robot Controllers"
date: 2018-09-16 03:39:23
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Robin Deits, Twan Koolen, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
Guided policy search is a popular approach for training controllers for high-dimensional systems, but it has a number of pitfalls. Non-convex trajectory optimization has local minima, and non-uniqueness in the optimal policy itself can mean that independently-optimized samples do not describe a coherent policy from which to train. We introduce LVIS, which circumvents the issue of local minima through global mixed-integer optimization and the issue of non-uniqueness through learning the optimal value function (or cost-to-go) rather than the optimal policy. To avoid the expense of solving the mixed-integer programs to full global optimality, we instead solve them only partially, extracting intervals containing the true cost-to-go from early termination of the branch-and-bound algorithm. These interval samples are used to weakly supervise the training of a neural net which approximates the true cost-to-go. Online, we use that learned cost-to-go as the terminal cost of a one-step model-predictive controller, which we solve via a small mixed-integer optimization. We demonstrate the LVIS approach on a cart-pole system with walls and a planar humanoid robot model and show that it can be applied to a fundamentally hard problem in feedback control--control through contact.

##### Abstract (translated by Google)
引导式策略搜索是一种用于训练高维系统控制器的流行方法，但它存在许多缺陷。非凸轨迹优化具有局部最小值，并且最优策略本身中的非唯一性可以意味着独立优化的样本不描述用于训练的连贯策略。我们介绍了LVIS，它通过全局混合整数优化来解决局部最小值问题，并通过学习最优值函数（或成本计算）而不是最优策略来解决非唯一性问题。为了避免将混合整数程序解决为全局最优性的代价，我们只是部分地解决它们，从早期终止分支定界算法中提取包含真实成本的间隔。这些区间样本用于弱监督神经网络的训练，该训练近似于真实的成本。在线，我们使用学到的成本作为一步模型预测控制器的终端成本，我们通过一个小的混合整数优化来解决。我们在带有墙壁和平面人形机器人模型的车 - 杆系统上展示了LVIS方法，并表明它可以应用于反馈控制中的一个根本性难题 - 通过接触进行控制。

##### URL
[http://arxiv.org/abs/1809.05802](http://arxiv.org/abs/1809.05802)

##### PDF
[http://arxiv.org/pdf/1809.05802](http://arxiv.org/pdf/1809.05802)

