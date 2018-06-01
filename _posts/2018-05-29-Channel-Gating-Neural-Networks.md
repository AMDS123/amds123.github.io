---
layout: post
title: "Channel Gating Neural Networks"
date: 2018-05-29 20:11:56
categories: arXiv_CV
tags: arXiv_CV Classification
author: Weizhe Hua, Christopher De Sa, Zhiru Zhang, G. Edward Suh
mathjax: true
---

* content
{:toc}

##### Abstract
Employing deep neural networks to obtain state-of-the-art performance on computer vision tasks can consume billions of floating point operations and several Joules of energy per evaluation. Network pruning, which statically removes unnecessary features and weights, has emerged as a promising way to reduce this computation cost. In this paper, we propose channel gating, a dynamic, fine-grained, training-based computation-cost-reduction scheme. Channel gating works by identifying the regions in the features which contribute less to the classification result and turning off a subset of the channels for computing the pixels within these uninteresting regions. Unlike static network pruning, the channel gating optimizes computations exploiting characteristics specific to each input at run-time. We show experimentally that applying channel gating in state-of-the-art networks can achieve 66% and 60% reduction in FLOPs with 0.22% and 0.29% accuracy loss on the CIFAR-10 and CIFAR-100 datasets, respectively.

##### Abstract (translated by Google)
使用深度神经网络获得计算机视觉任务的最新性能可能会消耗数十亿浮点运算和每次评估几焦耳的能量。网络修剪静态地去除不必要的特征和权重，已经成为减少这种计算成本的有希望的方式。在本文中，我们提出了信道门控，一种动态的，细粒度的，基于训练的计算 - 成本降低方案。通道门控通过识别对分类结果贡献较少的特征中的区域以及关闭用于计算这些不感兴趣区域内的像素的通道的子集来工作。与静态网络修剪不同，通道门控优化了在运行时利用特定于每个输入的特性的计算。我们通过实验证明，在最先进的网络中应用信道门控可以分别在CIFAR-10和CIFAR-100数据集上分别减少66％和60％的FLOP，精度损失分别为0.22％和0.29％。

##### URL
[http://arxiv.org/abs/1805.12549](http://arxiv.org/abs/1805.12549)

##### PDF
[http://arxiv.org/pdf/1805.12549](http://arxiv.org/pdf/1805.12549)

