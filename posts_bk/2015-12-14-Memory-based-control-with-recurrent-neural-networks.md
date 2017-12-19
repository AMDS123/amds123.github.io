---
layout: post
title: "Memory-based control with recurrent neural networks"
date: 2015-12-14 18:44:48
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning RNN
author: Nicolas Heess, Jonathan J Hunt, Timothy P Lillicrap, David Silver
mathjax: true
---

* content
{:toc}

##### Abstract
Partially observed control problems are a challenging aspect of reinforcement learning. We extend two related, model-free algorithms for continuous control -- deterministic policy gradient and stochastic value gradient -- to solve partially observed domains using recurrent neural networks trained with backpropagation through time. We demonstrate that this approach, coupled with long-short term memory is able to solve a variety of physical control problems exhibiting an assortment of memory requirements. These include the short-term integration of information from noisy sensors and the identification of system parameters, as well as long-term memory problems that require preserving information over many time steps. We also demonstrate success on a combined exploration and memory problem in the form of a simplified version of the well-known Morris water maze task. Finally, we show that our approach can deal with high-dimensional observations by learning directly from pixels. We find that recurrent deterministic and stochastic policies are able to learn similarly good solutions to these tasks, including the water maze where the agent must learn effective search strategies.

##### Abstract (translated by Google)
部分观察到的控制问题是强化学习的一个挑战。我们扩展了两个相关的，无模型的连续控制算法 - 确定性策略梯度和随机值梯度 - 用时间反向传播训练的递归神经网络来解决部分观察的域。我们证明，这种方法，加上长期的短期记忆能够解决各种物理控制问题，展现出各种各样的记忆需求。其中包括来自噪声传感器的信息的短期整合和系统参数的识别，以及长时间记忆问题，需要在很多时间步骤保存信息。我们还以一个着名的莫里斯水迷宫任务的简化版本的形式展示了一个综合的探索和记忆问题的成功。最后，我们表明，我们的方法可以通过直接从像素学习来处理高维观测。我们发现，经常性的确定性和随机性政策能够为这些任务学习类似的良好解决方案，包括代理人必须学习有效的搜索策略的水迷宫。

##### URL
[https://arxiv.org/abs/1512.04455](https://arxiv.org/abs/1512.04455)

##### PDF
[https://arxiv.org/pdf/1512.04455](https://arxiv.org/pdf/1512.04455)

