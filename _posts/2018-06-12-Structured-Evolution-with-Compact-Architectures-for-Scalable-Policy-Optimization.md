---
layout: post
title: "Structured Evolution with Compact Architectures for Scalable Policy Optimization"
date: 2018-06-12 14:52:29
categories: arXiv_RO
tags: arXiv_RO Optimization Inference
author: Krzysztof Choromanski, Mark Rowland, Vikas Sindhwani, Richard E. Turner, Adrian Weller
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new method of blackbox optimization via gradient approximation with the use of structured random orthogonal matrices, providing more accurate estimators than baselines and with provable theoretical guarantees. We show that this algorithm can be successfully applied to learn better quality compact policies than those using standard gradient estimation techniques. The compact policies we learn have several advantages over unstructured ones, including faster training algorithms and faster inference. These benefits are important when the policy is deployed on real hardware with limited resources. Further, compact policies provide more scalable architectures for derivative-free optimization (DFO) in high-dimensional spaces. We show that most robotics tasks from the OpenAI Gym can be solved using neural networks with less than 300 parameters, with almost linear time complexity of the inference phase, with up to 13x fewer parameters relative to the Evolution Strategies (ES) algorithm introduced by Salimans et al. (2017). We do not need heuristics such as fitness shaping to learn good quality policies, resulting in a simple and theoretically motivated training mechanism.

##### Abstract (translated by Google)
我们通过使用结构化随机正交矩阵的梯度逼近提出了一种新的黑箱优化方法，提供比基线更准确的估计量，并提供可证明的理论保证。我们表明，这种算法可以成功应用于学习比使用标准梯度估计技术更好的质量紧凑政策。我们学习的紧凑策略与非结构化策略相比有几个优点，包括更快的训练算法和更快的推理。当策略部署在资源有限的真实硬件上时，这些好处非常重要。此外，紧凑策略为高维空间中的无衍生优化（DFO）提供了更多可扩展架构。我们证明，使用少于300个参数的神经网络可以解决来自OpenAI Gym的大多数机器人任务，其中推理阶段的线性时间复杂度相对于Salimans引入的Evolution策略（ES）算法的参数少13倍等人。 （2017年）。我们不需要启发式方法，比如健身塑造来学习高质量的策略，从而产生一个简单的，理论上有动力的训练机制。

##### URL
[http://arxiv.org/abs/1804.02395](http://arxiv.org/abs/1804.02395)

##### PDF
[http://arxiv.org/pdf/1804.02395](http://arxiv.org/pdf/1804.02395)

