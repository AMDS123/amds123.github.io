---
layout: post
title: "Differentiable lower bound for expected BLEU score"
date: 2017-12-13 11:17:37
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Optimization
author: Vlad Zhukov, Maksim Kretov
mathjax: true
---

* content
{:toc}

##### Abstract
In natural language processing tasks performance of the models is often measured with some non-differentiable metric, such as BLEU score. To use efficient gradient-based methods for optimization, it is a common workaround to optimize some surrogate loss function. This approach is effective if optimization of such loss also results in improving target metric. The corresponding problem is referred to as loss-evaluation mismatch. In the present work we propose a method for calculation of differentiable lower bound of expected BLEU score that does not involve computationally expensive sampling procedure such as the one required when using REINFORCE rule from reinforcement learning (RL) framework.

##### Abstract (translated by Google)
在自然语言处理任务中，模型的表现通常用一些不可区分度量来度量，比如BLEU得分。要使用高效的基于梯度的方法进行优化，优化一些替代损失函数是一种常见的解决方法。这种方法是有效的，如果优化这种损失也导致改善目标度量。相应的问题被称为损失评估失配。在目前的工作中，我们提出了一种计算预期BLEU得分的可微下限的方法，该方法不涉及计算昂贵的抽样过程，例如从强化学习（RL）框架使用REINFORCE规则时所需的抽样过程。

##### URL
[http://arxiv.org/abs/1712.04708](http://arxiv.org/abs/1712.04708)

##### PDF
[http://arxiv.org/pdf/1712.04708](http://arxiv.org/pdf/1712.04708)

