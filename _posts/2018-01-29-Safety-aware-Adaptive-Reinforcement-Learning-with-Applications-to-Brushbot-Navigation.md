---
layout: post
title: "Safety-aware Adaptive Reinforcement Learning with Applications to Brushbot Navigation"
date: 2018-01-29 17:04:45
categories: arXiv_RO
tags: arXiv_RO Sparse Reinforcement_Learning Optimization
author: Motoya Ohnishi, Li Wang, Gennaro Notomista, Magnus Egerstedt
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a safety-aware learning framework that employs an adaptive model learning method together with barrier certificates for systems with possibly nonstationary agent dynamics. To extract the dynamic structure of the model, we use a sparse optimization technique, and the resulting model will be used in combination with control barrier certificates which constrain feedback controllers only when safety is about to be violated. Under some mild assumptions, solutions to the constrained feedback-controller optimization are guaranteed to be globally optimal, and the monotonic improvement of a feedback controller is thus ensured. In addition, we reformulate the (action-)value function approximation to make any kernel-based nonlinear function estimation method applicable. We then employ a state-of-the-art kernel adaptive filtering technique for the (action-)value function approximation. The resulting framework is verified experimentally on a brushbot, whose dynamics is unknown and highly complex.

##### Abstract (translated by Google)
本文提出了一个安全意识的学习框架，采用自适应模型学习方法连同障碍证书系统可能非平稳的代理动态。为了提取模型的动态结构，我们使用稀疏优化技术，结果模型将与控制障碍证书结合使用，控制障碍证书仅在安全性被违反时限制反馈控制器。在一些温和的假设下，约束反馈控制器优化的解决方案被保证是全局最优的，因此确保了反馈控制器的单调改进。另外，我们重新构造（作用）值函数近似，使得任何基于核的非线性函数估计方法都适用。然后，我们采用先进的内核自适应滤波技术进行（动作）值函数逼近。由此产生的框架通过brushbot实验验证，其动力学未知且非常复杂。

##### URL
[http://arxiv.org/abs/1801.09627](http://arxiv.org/abs/1801.09627)

##### PDF
[http://arxiv.org/pdf/1801.09627](http://arxiv.org/pdf/1801.09627)

