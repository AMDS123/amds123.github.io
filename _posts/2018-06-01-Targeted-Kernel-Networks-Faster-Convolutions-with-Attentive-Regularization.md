---
layout: post
title: "Targeted Kernel Networks: Faster Convolutions with Attentive Regularization"
date: 2018-06-01 19:46:16
categories: arXiv_CV
tags: arXiv_CV Regularization Attention CNN Inference
author: Kashyap Chitta
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Attentive Regularization (AR), a method to constrain the activation maps of kernels in Convolutional Neural Networks (CNNs) to specific regions of interest (ROIs). Each kernel learns a location of specialization along with its weights through standard backpropagation. A differentiable attention mechanism requiring no additional supervision is used to optimize the ROIs. Traditional CNNs of different types and structures can be modified with this idea into equivalent Targeted Kernel Networks (TKNs), while keeping the network size nearly identical. By restricting kernel ROIs, we reduce the number of sliding convolutional operations performed throughout the network in its forward pass, speeding up both training and inference. We evaluate our proposed architecture on both synthetic and natural tasks across multiple domains. TKNs obtain significant improvements over baselines, requiring less computation (around an order of magnitude) while achieving superior performance.

##### Abstract (translated by Google)
我们提出细致正则化（AR），一种将卷积神经网络（CNN）中的核的激活图约束到特定感兴趣区域（ROI）的方法。每个内核通过标准反向传播学习专业化位置及其权重。使用不需要额外监督的可区分的关注机制来优化投资回报率。不同类型和结构的传统CNN可以用这种思想修改为等效的目标核心网络（TKN），同时保持网络大小几乎相同。通过限制内核ROI，我们减少了正向遍历整个网络执行的滑动卷积操作的次数，加快了训练和推理。我们评估我们提出的跨多个领域的合成和自然任务的架构。 TKN在基线方面取得重大进展，需要更少的计算（大约一个数量级），同时实现卓越的性能。

##### URL
[http://arxiv.org/abs/1806.00523](http://arxiv.org/abs/1806.00523)

##### PDF
[http://arxiv.org/pdf/1806.00523](http://arxiv.org/pdf/1806.00523)

