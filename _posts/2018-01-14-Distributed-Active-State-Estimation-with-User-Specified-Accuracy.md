---
layout: post
title: "Distributed Active State Estimation with User-Specified Accuracy"
date: 2018-01-14 03:22:49
categories: arXiv_RO
tags: arXiv_RO Sparse Optimization
author: Charles Freundlich, Soomin Lee, Michael M. Zavlanos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of controlling a network of mobile sensors so that a set of hidden states are estimated up to a user-specified accuracy. The sensors take measurements and fuse them online using an Information Consensus Filter (ICF). At the same time, the local estimates guide the sensors to their next best configuration. This leads to an LMI-constrained optimization problem that we solve by means of a new distributed random approximate projections method. The new method is robust to the state disagreement errors that exist among the robots as the ICF fuses the collected measurements. Assuming that the noise corrupting the measurements is zero-mean and Gaussian and that the robots are self localized in the environment, the integrated system converges to the next best positions from where new observations will be taken. This process is repeated with the robots taking a sequence of observations until the hidden states are estimated up to the desired user-specified accuracy. We present simulations of sparse landmark localization, where the robotic team achieves the desired estimation tolerances while exhibiting interesting emergent behavior.

##### Abstract (translated by Google)
在本文中，我们解决了控制移动传感器网络的问题，以便根据用户指定的精度估计一组隐藏状态。传感器采用信息共识过滤器（ICF）进行测量并在线融合。与此同时，当地的估算指导传感器达到下一个最佳配置。这导致了LMI约束优化问题，我们通过一种新的分布式随机近似投影方法来解决。由于ICF融合了所收集的测量数据，所以新方法对机器人之间存在的状态不一致错误具有鲁棒性。假设损坏测量结果的噪声是零均值和高斯的，并且机器人在环境中是自我定位的，那么综合系统会收敛到下一个最佳位置，从那里进行新的观察。机器人重复这个过程，进行一系列的观察，直到隐藏状态估计达到用户指定的精度。我们提出稀疏的地标本地化的模拟，机器人团队达到期望的估计公差，同时展示有趣的紧急行为。

##### URL
[http://arxiv.org/abs/1706.01576](http://arxiv.org/abs/1706.01576)

##### PDF
[http://arxiv.org/pdf/1706.01576](http://arxiv.org/pdf/1706.01576)

