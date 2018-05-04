---
layout: post
title: "Formal Security Analysis of Neural Networks using Symbolic Intervals"
date: 2018-04-28 16:37:01
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization
author: Shiqi Wang, Kexin Pei, Justin Whitehouse, Junfeng Yang, Suman Jana
mathjax: true
---

* content
{:toc}

##### Abstract
Due to the increasing deployment of Deep Neural Networks (DNNs) in real-world security-critical domains including autonomous vehicles and collision avoidance systems, formally checking security properties of DNNs, especially under different attacker capabilities, is becoming crucial. Most existing security testing techniques for DNNs try to find adversarial examples without providing any formal security guarantees about the non-existence of adversarial examples. Recently, several projects have used different types of Satisfiability Modulo Theory (SMT) solvers to formally check security properties of DNNs. However, all of these approaches are limited by the high overhead caused by the solver. In this paper, we present a new direction for formally checking security properties of DNNs without using SMT solvers. Instead, we leverage interval arithmetic to formally check security properties by computing rigorous bounds on the DNN outputs. Our approach, unlike existing solver-based approaches, is easily parallelizable. We further present symbolic interval analysis along with several other optimizations to minimize overestimations. We design, implement, and evaluate our approach as part of ReluVal, a system for formally checking security properties of Relu-based DNNs. Our extensive empirical results show that ReluVal outperforms Reluplex, a state-of-the-art solver-based system, by 200 times on average for the same security properties. ReluVal is able to prove a security property within 4 hours on a single 8-core machine without GPUs, while Reluplex deemed inconclusive due to timeout (more than 5 days). Our experiments demonstrate that symbolic interval analysis is a promising new direction towards rigorously analyzing different security properties of DNNs.

##### Abstract (translated by Google)
由于深度神经网络（DNN）在真实世界安全关键领域（包括自动车辆和防碰撞系统）中的部署日益增多，因此正式检查DNN的安全特性（尤其是在不同的攻击者能力下）正变得至关重要。大多数现有的DNN安全测试技术试图找到敌对的例子，而不提供关于不存在敌对的例子的任何正式的安全保证。最近，一些项目已经使用了不同类型的可满足模数理论（SMT）求解器来正式检查DNN的安全属性。然而，所有这些方法都受到求解器造成的高开销的限制。在本文中，我们提出了一个新的方向，即在不使用SMT求解器的情况下正式检查DNN的安全属性。相反，我们利用区间算法通过计算DNN输出的严格界限来正式检查安全属性。与现有的基于求解器的方法不同，我们的方法很容易并行化。我们进一步提出符号间隔分析以及其他几种优化，以最大限度地降低估计过高。我们设计，实施和评估我们的方法，作为ReluVal的一部分，这是一个正式检查基于Relu的DNN安全属性的系统。我们广泛的实证结果显示，ReluVal比同类安全属性平均提升200倍，优于基于最新解算器的系统Reluplex。 ReluVal能够在没有GPU的单个8核机器上在4小时内证明安全属性，而Reluplex由于超时（超过5天）而被视为不确定。我们的实验证明，符号区间分析是一种有前途的新方向，可以严格分析DNN的不同安全属性。

##### URL
[https://arxiv.org/abs/1804.10829](https://arxiv.org/abs/1804.10829)

##### PDF
[https://arxiv.org/pdf/1804.10829](https://arxiv.org/pdf/1804.10829)

