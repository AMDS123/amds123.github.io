---
layout: post
title: "Sample-efficient Actor-Critic Reinforcement Learning with Supervised Data for Dialogue Management"
date: 2017-07-05 08:55:16
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Pei-Hao Su, Pawel Budzianowski, Stefan Ultes, Milica Gasic, Steve Young
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning (RL) methods have significant potential for dialogue policy optimisation. However, they suffer from a poor performance in the early stages of learning. This is especially problematic for on-line learning with real users. Two approaches are introduced to tackle this problem. Firstly, to speed up the learning process, two sample-efficient neural networks algorithms: trust region actor-critic with experience replay (TRACER) and episodic natural actor-critic with experience replay (eNACER) are presented. For TRACER, the trust region helps to control the learning step size and avoid catastrophic model changes. For eNACER, the natural gradient identifies the steepest ascent direction in policy space to speed up the convergence. Both models employ off-policy learning with experience replay to improve sample-efficiency. Secondly, to mitigate the cold start issue, a corpus of demonstration data is utilised to pre-train the models prior to on-line reinforcement learning. Combining these two approaches, we demonstrate a practical approach to learn deep RL-based dialogue policies and demonstrate their effectiveness in a task-oriented information seeking domain.

##### Abstract (translated by Google)
深度强化学习（RL）方法在对话政策优化方面具有巨大的潜力。然而，他们在学习的早期阶段表现不佳。这对于真实用户的在线学习尤其成问题。引入两种方法来解决这个问题。首先，为了加快学习过程，提出了两个样本有效的神经网络算法：带有经验回放的信赖域行为者 - 评论者（TRACER）和带有经验回放的情景自然行为者 - 评论者（eNACER）。对于TRACER，信任区域有助于控制学习步长，避免灾难性的模型变更。对于eNACER来说，自然梯度标识了政策空间中最陡峭的上升方向，以加速融合。这两种模式都采用了带有经验回放的非政策学习来提高样本效率。其次，为了缓解冷启动问题，在线强化学习之前，利用一系列演示数据对模型进行预训练。结合这两种方法，我们展示了一种实用的方法来学习深入的基于RL的对话策略，并展示其在面向任务的信息搜索领域的有效性。

##### URL
[https://arxiv.org/abs/1707.00130](https://arxiv.org/abs/1707.00130)

##### PDF
[https://arxiv.org/pdf/1707.00130](https://arxiv.org/pdf/1707.00130)

