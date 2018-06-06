---
layout: post
title: "Deep Mixture of Experts via Shallow Embedding"
date: 2018-06-05 07:41:04
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Reinforcement_Learning Embedding CNN
author: Xin Wang, Fisher Yu, Ruth Wang, Yi-An Ma, Azalia Mirhoseini, Trevor Darrell, Joseph E. Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Larger networks generally have greater representational power at the cost of increased computational complexity. Sparsifying such networks has been an active area of research but has been generally limited to static regularization or dynamic approaches using reinforcement learning. We explore a mixture of experts (MoE) approach to deep dynamic routing, which activates certain experts in the network on a per-example basis. Our novel DeepMoE architecture increases the representational power of standard convolutional networks by adaptively sparsifying and recalibrating channel-wise features in each convolutional layer. We employ a multi-headed sparse gating network to determine the selection and scaling of channels for each input, leveraging exponential combinations of experts within a single convolutional network. Our proposed architecture is evaluated on several benchmark datasets and tasks and we show that DeepMoEs are able to achieve higher accuracy with lower computation than standard convolutional networks.

##### Abstract (translated by Google)
较大的网络通常以增加的计算复杂度为代价具有更大的表示能力。分散这种网络一直是一个活跃的研究领域，但一般限于静态正则化或使用强化学习的动态方法。我们探索了多种专家（MoE）方法来实现深度动态路由，从而在每个示例的基础上激活网络中的某些专家。我们的小说DeepMoE体系结构通过自适应稀疏化和重新校准每个卷积层中的通道方面的特性，提高了标准卷积网络的代表性能力。我们采用多头稀疏选通网络来确定每个输入信道的选择和缩放，并利用单个卷积网络内专家的指数组合。我们提出的架构在几个基准数据集和任务上进行评估，我们证明DeepMoE能够以比标准卷积网络更低的计算实现更高的准确性。

##### URL
[http://arxiv.org/abs/1806.01531](http://arxiv.org/abs/1806.01531)

##### PDF
[http://arxiv.org/pdf/1806.01531](http://arxiv.org/pdf/1806.01531)

