---
layout: post
title: "Best arm identification in multi-armed bandits with delayed feedback"
date: 2018-03-29 06:46:38
categories: arXiv_AI
tags: arXiv_AI Optimization Relation
author: Aditya Grover, Todor Markov, Peter Attia, Norman Jin, Nicholas Perkins, Bryan Cheong, Michael Chen, Zi Yang, Stephen Harris, William Chueh, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a generalization of the best arm identification problem in stochastic multi-armed bandits (MAB) to the setting where every pull of an arm is associated with delayed feedback. The delay in feedback increases the effective sample complexity of standard algorithms, but can be offset if we have access to partial feedback received before a pull is completed. We propose a general framework to model the relationship between partial and delayed feedback, and as a special case we introduce efficient algorithms for settings where the partial feedback are biased or unbiased estimators of the delayed feedback. Additionally, we propose a novel extension of the algorithms to the parallel MAB setting where an agent can control a batch of arms. Our experiments in real-world settings, involving policy search and hyperparameter optimization in computational sustainability domains for fast charging of batteries and wildlife corridor construction, demonstrate that exploiting the structure of partial feedback can lead to significant improvements over baselines in both sequential and parallel MAB.

##### Abstract (translated by Google)
我们提出将随机多臂匪（MAB）中最好的胳膊识别问题推广到手臂的每次拉动均与延迟反馈相关的情况。反馈延迟会增加标准算法的有效采样复杂度，但如果我们可以访问在完成拉取操作之前收到的部分反馈，则可以抵消延迟。我们提出了一个通用框架来模拟部分反馈和延迟反馈之间的关系，作为一种特殊情况，我们介绍了部分反馈偏置或无偏估计延迟反馈的设置的高效算法。此外，我们提出了一种新的算法扩展到并行MAB设置，代理可以控制一批武器。我们在现实环境中进行的实验包括策略搜索和计算可持续发展领域的超参数优化，以实现电池快速充电和野生动物走廊建设，表明利用部分反馈结构可以显着改善顺序和并行MAB中的基线。

##### URL
[http://arxiv.org/abs/1803.10937](http://arxiv.org/abs/1803.10937)

##### PDF
[http://arxiv.org/pdf/1803.10937](http://arxiv.org/pdf/1803.10937)

