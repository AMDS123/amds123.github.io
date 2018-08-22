---
layout: post
title: "Differentiable lower bound for expected BLEU score"
date: 2018-08-21 08:55:07
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Optimization
author: Vlad Zhukov, Eugene Golikov, Maksim Kretov
mathjax: true
---

* content
{:toc}

##### Abstract
In natural language processing tasks performance of the models is often measured with some non-differentiable metric, such as BLEU score. To use efficient gradient-based methods for optimization, it is a common workaround to optimize some surrogate loss function. This approach is effective if optimization of such loss also results in improving target metric. The corresponding problem is referred to as loss-evaluation mismatch. In the present work we propose a method for calculation of differentiable lower bound of expected BLEU score that does not involve computationally expensive sampling procedure such as the one required when using REINFORCE rule from reinforcement learning (RL) framework.

##### Abstract (translated by Google)
在自然语言处理任务中，模型的性能通常用一些不可微的度量来衡量，例如BLEU得分。要使用有效的基于梯度的方法进行优化，优化某些替代损失函数是一种常见的解决方法。如果这种损失的优化也导致改进目标度量，则该方法是有效的。相应的问题被称为损失评估不匹配。在目前的工作中，我们提出了一种计算预期BLEU分数的可微分下界的方法，该方法不涉及计算上昂贵的抽样程序，例如当使用来自强化学习（RL）框架的REINFORCE规则时所需的抽样程序。

##### URL
[http://arxiv.org/abs/1712.04708](http://arxiv.org/abs/1712.04708)

##### PDF
[http://arxiv.org/pdf/1712.04708](http://arxiv.org/pdf/1712.04708)

