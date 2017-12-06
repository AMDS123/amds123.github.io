---
layout: post
title: "Towards Faster Training of Global Covariance Pooling Networks by Iterative Matrix Square Root Normalization"
date: 2017-12-04 12:22:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Peihua Li, Jiangtao Xie, Qilong Wang, Zilin Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Global covariance pooling in Convolutional neural neworks has achieved impressive improvement over the classical first-order pooling. Recent works have shown matrix square root normalization plays a central role in achieving state-of-the-art performance. However, existing methods depending heavily on eigenvalue decomposition (EIG) or singular value decomposition (SVD), suffering from inefficient training due to limited support of EIG and SVD on GPU. Towards addressing this problem, we propose an iterative matrix square root normalization method for end-to-end training of covariance pooling networks. At the core of our method is a meta-layer designed with loop-embedded directed graph structure. The meta-layer consists of three consecutive nonlinear structured layers, which perform pre-normalization, coupled matrix iteration and post-compensation, respectively. Our method is much faster than EIG or SVD based ones, since it involves only matrix multiplications, suitable for parallel implementation on GPU. Moreover, the proposed network with ResNet architecture can converge in much less epochs, further accelerating network training. On large-scale ImageNet, we achieve competitive performance superior to existing covariance pooling networks. By finetuning our models pretrained on ImageNet, we establish state-of-the-art results on three challenging fine-grained benchmarks.

##### Abstract (translated by Google)
卷积神经网络中的全局协方差集合在经典的一阶集中方面取得了显着的进步。最近的研究表明矩阵平方根归一化在实现最先进的性能方面起着核心作用。然而，现有的方法主要依赖于特征值分解（EIG）或奇异值分解（SVD），由于EIG和SVD在GPU上的有限支持而受到无效训练的困扰。针对这个问题，我们提出了一种迭代矩阵平方根归一化方法，用于协方差池网络的端到端训练。我们方法的核心是一个设计有循环嵌入的有向图结构的元层。元层由三个连续的非线性结构层组成，分别进行预标准化，耦合矩阵迭代和后置补偿。我们的方法比基于EIG或SVD的方法快得多，因为它只涉及矩阵乘法，适合GPU上的并行实现。此外，所提出的具有ResNet架构的网络能够以更少的时间收敛，进一步加速网络训练。在大规模的ImageNet上，我们实现了比现有协方差池网络更好的竞争性能。通过在ImageNet上预训练我们的模型，我们在三个具有挑战性的细粒度基准上建立了最先进的结果。

##### URL
[http://arxiv.org/abs/1712.01034](http://arxiv.org/abs/1712.01034)

