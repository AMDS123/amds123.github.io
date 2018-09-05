---
layout: post
title: "Latent Space Policies for Hierarchical Reinforcement Learning"
date: 2018-09-03 19:24:16
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Tuomas Haarnoja, Kristian Hartikainen, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of learning hierarchical deep neural network policies for reinforcement learning. In contrast to methods that explicitly restrict or cripple lower layers of a hierarchy to force them to use higher-level modulating signals, each layer in our framework is trained to directly solve the task, but acquires a range of diverse strategies via a maximum entropy reinforcement learning objective. Each layer is also augmented with latent random variables, which are sampled from a prior distribution during the training of that layer. The maximum entropy objective causes these latent variables to be incorporated into the layer's policy, and the higher level layer can directly control the behavior of the lower layer through this latent space. Furthermore, by constraining the mapping from latent variables to actions to be invertible, higher layers retain full expressivity: neither the higher layers nor the lower layers are constrained in their behavior. Our experimental evaluation demonstrates that we can improve on the performance of single-layer policies on standard benchmark tasks simply by adding additional layers, and that our method can solve more complex sparse-reward tasks by learning higher-level policies on top of high-entropy skills optimized for simple low-level objectives.

##### Abstract (translated by Google)
我们解决了学习用于强化学习的分层深度神经网络策略的问题。与明确限制或削弱层次结构的较低层以强制它们使用更高级别调制信号的方法相比，我们框架中的每个层都经过培训以直接解决任务，但通过最大熵增强获得了一系列不同的策略学习目标。每个层还使用潜在随机变量进行增强，潜在随机变量在该层的训练期间从先前分布中采样。最大熵目标导致这些潜在变量被合并到层的策略中，而更高层的层可以通过该潜在空间直接控制下层的行为。此外，通过将映射从潜在变量约束为可逆的动作，较高层保持完全表达性：较高层和较低层都不受其行为的约束。我们的实验评估表明，我们可以通过添加额外的层来改进单层策略在标准基准任务上的性能，并且我们的方法可以通过在高熵之上学习更高级别的策略来解决更复杂的稀疏奖励任务为简单的低级目标优化的技能。

##### URL
[http://arxiv.org/abs/1804.02808](http://arxiv.org/abs/1804.02808)

##### PDF
[http://arxiv.org/pdf/1804.02808](http://arxiv.org/pdf/1804.02808)

