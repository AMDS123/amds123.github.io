---
layout: post
title: "PoseAgent: Budget-Constrained 6D Object Pose Estimation via Reinforcement Learning"
date: 2017-04-11 08:24:22
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Reinforcement_Learning
author: Alexander Krull, Eric Brachmann, Sebastian Nowozin, Frank Michel, Jamie Shotton, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art computer vision algorithms often achieve efficiency by making discrete choices about which hypotheses to explore next. This allows allocation of computational resources to promising candidates, however, such decisions are non-differentiable. As a result, these algorithms are hard to train in an end-to-end fashion. In this work we propose to learn an efficient algorithm for the task of 6D object pose estimation. Our system optimizes the parameters of an existing state-of-the art pose estimation system using reinforcement learning, where the pose estimation system now becomes the stochastic policy, parametrized by a CNN. Additionally, we present an efficient training algorithm that dramatically reduces computation time. We show empirically that our learned pose estimation procedure makes better use of limited resources and improves upon the state-of-the-art on a challenging dataset. Our approach enables differentiable end-to-end training of complex algorithmic pipelines and learns to make optimal use of a given computational budget.

##### Abstract (translated by Google)
最先进的计算机视觉算法通常通过对接下来要探索的假设进行离散选择来实现效率。这允许将计算资源分配给有希望的候选者，然而，这样的决定是不可区分的。结果，这些算法很难以端对端的方式进行训练。在这项工作中，我们建议学习6D对象姿态估计任务的高效算法。我们的系统使用强化学习来优化现有技术的姿态估计系统的参数，其中姿态估计系统现在成为由CNN参数化的随机策略。此外，我们提出了一个高效的训练算法，大大减少了计算时间。我们凭经验显示，我们学习的姿势估计程序更好地利用有限的资源，并改进了具有挑战性的数据集的最新技术。我们的方法能够对复杂的算法流水线进行可区分的端到端培训，并学习如何最优化地使用给定的计算预算。

##### URL
[https://arxiv.org/abs/1612.03779](https://arxiv.org/abs/1612.03779)

##### PDF
[https://arxiv.org/pdf/1612.03779](https://arxiv.org/pdf/1612.03779)

