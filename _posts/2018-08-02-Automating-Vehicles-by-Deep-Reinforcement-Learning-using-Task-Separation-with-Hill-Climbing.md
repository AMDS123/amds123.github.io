---
layout: post
title: "Automating Vehicles by Deep Reinforcement Learning using Task Separation with Hill Climbing"
date: 2018-08-02 12:49:52
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning Optimization
author: Mogens Graf Plessen
mathjax: true
---

* content
{:toc}

##### Abstract
Within the context of autonomous driving a model-based reinforcement learning algorithm is proposed for the design of neural network-parameterized controllers. Classical model-based control methods, which include sampling- and lattice-based algorithms and model predictive control, suffer from the trade-off between model complexity and computational burden required for the online solution of expensive optimization or search problems at every short sampling time. To circumvent this trade-off, a 2-step procedure is motivated: first learning of a controller during offline training based on an arbitrarily complicated mathematical system model, before online fast feedforward evaluation of the trained controller. The contribution of this paper is the proposition of a simple gradient-free and model-based algorithm for deep reinforcement learning using task separation with hill climbing (TSHC). In particular, (i) simultaneous training on separate deterministic tasks with the purpose of encoding many motion primitives in a neural network, and (ii) the employment of maximally sparse rewards in combination with virtual velocity constraints (VVCs) in setpoint proximity are advocated.

##### Abstract (translated by Google)
在自动驾驶的背景下，提出了一种基于模型的强化学习算法，用于神经网络参数化控制器的设计。基于经典模型的控制方法（包括基于采样和基于格的算法和模型预测控制）受到模型复杂性和在每个短采样时间的在线解决昂贵的优化或搜索问题所需的计算负担之间的折衷。为了避免这种权衡，需要采取两步程序：在训练控制器的在线快速前馈评估之前，首先基于任意复杂的数学系统模型在离线训练期间学习控制器。本文的贡献是提出了一种简单的无梯度和基于模型的深度强化学习算法，该算法使用爬山任务分离（TSHC）。特别地，（i）同时训练单独的确定性任务，目的是在神经网络中编码许多运动基元，以及（ii）提供最大稀疏奖励与设定点接近度中的虚拟速度约束（VVC）的结合。

##### URL
[http://arxiv.org/abs/1711.10785](http://arxiv.org/abs/1711.10785)

##### PDF
[http://arxiv.org/pdf/1711.10785](http://arxiv.org/pdf/1711.10785)

