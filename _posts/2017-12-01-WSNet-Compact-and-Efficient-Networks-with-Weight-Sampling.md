---
layout: post
title: "WSNet: Compact and Efficient Networks with Weight Sampling"
date: 2017-12-01 05:11:35
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xiaojie Jin, Yingzhen Yang, Ning Xu, Jianchao Yang, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach and a novel architecture, termed WSNet, for learning compact and efficient deep neural networks. Existing approaches conventionally learn full model parameters independently at first and then compress them via ad hoc processing like model pruning or filter factorization. Different from them, WSNet proposes learning model parameters by sampling from a compact set of learnable parameters, which naturally enforces parameter sharing throughout the learning process. We show that such novel weight sampling approach (and induced WSNet) promotes both weights and computation sharing favorably. It can more efficiently learn much smaller networks with competitive performance, compared to baseline networks with equal number of convolution filters. Specifically, we consider learning compact and efficient 1D convolutional neural networks for audio classification. Extensive experiments on multiple audio classification datasets verify the effectiveness of WSNet. Combined with weight quantization, the resulted models are up to 180x smaller and theoretically up to 16x faster than the well-established baselines, without noticeable performance drop.

##### Abstract (translated by Google)
我们提出了一个新的方法和一个新的架构，被称为WSNet，用于学习紧凑和高效的深度神经网络。现有的方法通常首先独立地学习全模型参数，然后通过诸如模型修剪或过滤因子分解之类的临时处理来压缩它们。与之不同的是，WSNet通过从一系列可学习的参数中抽取样本来提出学习模型参数，这自然地在整个学习过程中强制参数共享。我们表明，这种新颖的权重抽样方法（和诱导WSNet）有利地促进了权重和计算分享。与具有相同数量的卷积滤波器的基线网络相比，它可以更有效地学习具有竞争性能的更小的网络。具体来说，我们考虑学习紧凑高效的一维卷积神经网络的音频分类。在多个音频分类数据集上的大量实验验证了WSNet的有效性。与重量量化相结合，所得模型的尺寸缩小了180倍，从理论上来说，比完善的基线快了16倍，而性能却没有明显的下降。

##### URL
[https://arxiv.org/abs/1711.10067](https://arxiv.org/abs/1711.10067)

##### PDF
[https://arxiv.org/pdf/1711.10067](https://arxiv.org/pdf/1711.10067)

