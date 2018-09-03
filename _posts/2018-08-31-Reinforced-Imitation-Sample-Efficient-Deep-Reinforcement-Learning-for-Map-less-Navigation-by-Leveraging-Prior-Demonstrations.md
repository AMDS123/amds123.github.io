---
layout: post
title: "Reinforced Imitation: Sample Efficient Deep Reinforcement Learning for Map-less Navigation by Leveraging Prior Demonstrations"
date: 2018-08-31 09:04:21
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning
author: Mark Pfeiffer, Samarth Shukla, Matteo Turchetta, Cesar Cadena, Andreas Krause, Roland Siegwart, Juan Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a case study of a learning-based approach for target driven map-less navigation. The underlying navigation model is an end-to-end neural network which is trained using a combination of expert demonstrations, imitation learning (IL) and reinforcement learning (RL). While RL and IL suffer from a large sample complexity and the distribution mismatch problem, respectively, we show that leveraging prior expert demonstrations for pre-training can reduce the training time to reach at least the same level of performance compared to plain RL by a factor of 5. We present a thorough evaluation of different combinations of expert demonstrations, different RL algorithms and reward functions, both in simulation and on a real robotic platform. Our results show that the final model outperforms both standalone approaches in the amount of successful navigation tasks. In addition, the RL reward function can be significantly simplified when using pre-training, e.g. by using a sparse reward only. The learned navigation policy is able to generalize to unseen and real-world environments.

##### Abstract (translated by Google)
这项工作提出了一个基于学习的方法的案例研究，用于目标驱动的无地图导航。底层导航模型是端到端神经网络，其使用专家演示，模仿学习（IL）和强化学习（RL）的组合进行训练。虽然RL和IL分别遭受大样本复杂性和分布不匹配问题，但我们表明，利用先前的专家演示进行预训练可以减少训练时间，以便与普通RL相比达到至少相同的性能水平5.我们提供了对模拟和真实机器人平台上的专家演示，不同RL算法和奖励函数的不同组合的全面评估。我们的结果表明，最终模型在成功导航任务的数量上优于两种独立方法。此外，当使用预训练时，例如RL奖励功能可以被显着简化。仅使用稀疏奖励。学习的导航策略能够概括为看不见的和真实的环境。

##### URL
[http://arxiv.org/abs/1805.07095](http://arxiv.org/abs/1805.07095)

##### PDF
[http://arxiv.org/pdf/1805.07095](http://arxiv.org/pdf/1805.07095)

