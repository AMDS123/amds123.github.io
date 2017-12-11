---
layout: post
title: "Improving Negative Sampling for Word Representation using Self-embedded Features"
date: 2017-12-08 18:40:22
categories: arXiv_CL
tags: arXiv_CL Gradient_Descent
author: Long Chen, Fajie Yuan, Joemon M. Jose, Weinan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Although the word-popularity based negative sampler has shown superb performance in the skip-gram model, the theoretical motivation behind oversampling popular (non-observed) words as negative samples is still not well understood. In this paper, we start from an investigation of the gradient vanishing issue in the skip-gram model without a proper negative sampler. By performing an insightful analysis from the stochastic gradient descent (SGD) learning perspective, we demonstrate that, both theoretically and intuitively, negative samples with larger inner product scores are more informative than those with lower scores for the SGD learner in terms of both convergence rate and accuracy. Understanding this, we propose an alternative sampling algorithm that dynamically selects informative negative samples during each SGD update. More importantly, the proposed sampler accounts for multi-dimensional self-embedded features during the sampling process, which essentially makes it more effective than the original popularity-based (one-dimensional) sampler. Empirical experiments further verify our observations, and show that our fine-grained samplers gain significant improvement over the existing ones without increasing computational complexity.

##### Abstract (translated by Google)
尽管基于单词普及的负面采样器在跳跃模型中表现出极好的表现，但是将流行（未观察到的）过度采样作为负面样本背后的理论动机还不是很清楚。在本文中，我们从没有适当的负采样器的skip-gram模型中的梯度消失问题开始。通过从随机梯度下降（SGD）学习的角度进行深入的分析，我们证明，从理论和直观上看，具有较大内积分数的负样本比收敛率较低的SGD学习者的信息量更多和准确性。了解这一点，我们提出了一种替代抽样算法，在每次SGD更新期间动态选择信息性负面样本。更重要的是，采样器在采样过程中考虑了多维自嵌入特性，基本上使其比原来基于流行的（一维）采样器更有效。经验实验进一步验证了我们的观察结果，并且表明我们的细粒度采样器在不增加计算复杂度的情况下比现有的采样器有了显着的改进。

##### URL
[http://arxiv.org/abs/1710.09805](http://arxiv.org/abs/1710.09805)

##### PDF
[http://arxiv.org/pdf/1710.09805](http://arxiv.org/pdf/1710.09805)

