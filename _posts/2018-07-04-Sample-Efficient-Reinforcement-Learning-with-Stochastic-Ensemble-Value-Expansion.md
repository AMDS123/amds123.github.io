---
layout: post
title: "Sample-Efficient Reinforcement Learning with Stochastic Ensemble Value Expansion"
date: 2018-07-04 16:51:56
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jacob Buckman, Danijar Hafner, George Tucker, Eugene Brevdo, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Integrating model-free and model-based approaches in reinforcement learning has the potential to achieve the high performance of model-free algorithms with low sample complexity. However, this is difficult because an imperfect dynamics model can degrade the performance of the learning algorithm, and in sufficiently complex environments, the dynamics model will almost always be imperfect. As a result, a key challenge is to combine model-based approaches with model-free learning in such a way that errors in the model do not degrade performance. We propose stochastic ensemble value expansion (STEVE), a novel model-based technique that addresses this issue. By dynamically interpolating between model rollouts of various horizon lengths for each individual example, STEVE ensures that the model is only utilized when doing so does not introduce significant errors. Our approach outperforms model-free baselines on challenging continuous control benchmarks with an order-of-magnitude increase in sample efficiency, and in contrast to previous model-based approaches, performance does not degrade in complex environments.

##### Abstract (translated by Google)
在强化学习中集成无模型和基于模型的方法有可能实现低样本复杂度的无模型算法的高性能。然而，这很困难，因为不完美的动力学模型会降低学习算法的性能，并且在足够复杂的环境中，动力学模型几乎总是不完美的。因此，一个关键的挑战是将基于模型的方法与无模型学习相结合，使模型中的错误不会降低性能。我们提出了随机集合值扩展（STEVE），这是一种基于模型的新技术，可以解决这个问题。通过在每个单独示例的各种地平线长度的模型卷展栏之间进行动态插值，STEVE确保仅在不会引入重大错误时才使用该模型。我们的方法在具有挑战性的连续控制基准测试中优于无模型基线，样本效率提高了数量级，与之前基于模型的方法相比，复杂环境中的性能不会降低。

##### URL
[http://arxiv.org/abs/1807.01675](http://arxiv.org/abs/1807.01675)

##### PDF
[http://arxiv.org/pdf/1807.01675](http://arxiv.org/pdf/1807.01675)

