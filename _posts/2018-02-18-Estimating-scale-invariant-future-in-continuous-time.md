---
layout: post
title: "Estimating scale-invariant future in continuous time"
date: 2018-02-18 19:09:28
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Relation
author: Zoran Tiganj, Samuel J. Gershman, Per B. Sederberg, Marc W. Howard
mathjax: true
---

* content
{:toc}

##### Abstract
Natural learners must compute an estimate of future outcomes that follow from a stimulus in continuous time. Critically, the learner cannot in general know a priori the relevant time scale over which meaningful relationships will be observed. Widely used reinforcement learning algorithms discretize continuous time and use the Bellman equation to estimate exponentially-discounted future reward. However, exponential discounting introduces a time scale to the computation of value. Scaling is a serious problem in continuous time: efficient learning with scaled algorithms requires prior knowledge of the relevant scale. That is, with scaled algorithms one must know at least part of the solution to a problem prior to attempting a solution. We present a computational mechanism, developed based on work in psychology and neuroscience, for computing a scale-invariant timeline of future events. This mechanism efficiently computes a model for future time on a logarithmically-compressed scale, and can be used to generate a scale-invariant power-law-discounted estimate of expected future reward. Moreover, the representation of future time retains information about what will happen when, enabling flexible decision making based on future events. The entire timeline can be constructed in a single parallel operation.

##### Abstract (translated by Google)
自然的学习者必须计算连续时间刺激后的未来结果的估计值。关键的是，学习者通常无法事先知道观察到有意义关系的相关时间范围。广泛使用的强化学习算法将连续时间离散化，并使用Bellman方程来估计指数式折扣未来奖励。然而，指数贴现为价值计算引入了一个时间尺度。缩放是连续时间中的一个严重问题：使用缩放算法的高效学习需要事先了解相关比例。也就是说，使用缩放算法，在尝试解决方案之前，必须知道解决方案的至少一部分。我们提出了一个计算机制，基于心理学和神经科学工作开发，用于计算未来事件的尺度不变时间轴。该机制有效地计算未来时间的对数压缩规模模型，并可用于生成预期未来报酬的尺度不变幂律贴现估计。此外，未来时间的表示保留了关于什么时候会发生的信息，从而根据未来事件做出灵活的决策。整个时间线可以在一个并行操作中构建。

##### URL
[http://arxiv.org/abs/1802.06426](http://arxiv.org/abs/1802.06426)

##### PDF
[http://arxiv.org/pdf/1802.06426](http://arxiv.org/pdf/1802.06426)

