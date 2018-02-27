---
layout: post
title: "A Simple Neural Attentive Meta-Learner"
date: 2018-02-25 04:55:20
categories: arXiv_AI
tags: arXiv_AI Attention Reinforcement_Learning
author: Nikhil Mishra, Mostafa Rohaninejad, Xi Chen, Pieter Abbeel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks excel in regimes with large amounts of data, but tend to struggle when data is scarce or when they need to adapt quickly to changes in the task. In response, recent work in meta-learning proposes training a meta-learner on a distribution of similar tasks, in the hopes of generalization to novel but related tasks by learning a high-level strategy that captures the essence of the problem it is asked to solve. However, many recent meta-learning approaches are extensively hand-designed, either using architectures specialized to a particular application, or hard-coding algorithmic components that constrain how the meta-learner solves the task. We propose a class of simple and generic meta-learner architectures that use a novel combination of temporal convolutions and soft attention; the former to aggregate information from past experience and the latter to pinpoint specific pieces of information. In the most extensive set of meta-learning experiments to date, we evaluate the resulting Simple Neural AttentIve Learner (or SNAIL) on several heavily-benchmarked tasks. On all tasks, in both supervised and reinforcement learning, SNAIL attains state-of-the-art performance by significant margins.

##### Abstract (translated by Google)
深度神经网络在拥有大量数据的机制中表现优异，但在数据稀缺或需要快速适应任务变化时往往会陷入困境。作为回应，最近在元学习方面的工作提出了对类似任务分配的元学习者进行培训，希望通过学习一个高层次的策略来概括新的但相关的任务，这个策略捕捉了被问到的问题的本质解决。然而，许多最近的元学习方法都是手工设计的，或者使用专门针对特定应用的体系结构，或者是硬编码的算法组件来限制元学习者解决任务的方式。我们提出了一类简单和通用的元学习者体系结构，它们使用了时间卷积和软性注意的新颖组合;前者汇总过去经验中的信息，后者则精确定位特定的信息。在迄今为止最广泛的元学习实验中，我们评估了由几个严重基准测试任务产生的Simple Neural AttentIve Learner（或SNAIL）。在所有任务中，无论是在监督和强化学习中，SNAIL都以显着的利润获得了最先进的表现。

##### URL
[http://arxiv.org/abs/1707.03141](http://arxiv.org/abs/1707.03141)

##### PDF
[http://arxiv.org/pdf/1707.03141](http://arxiv.org/pdf/1707.03141)

