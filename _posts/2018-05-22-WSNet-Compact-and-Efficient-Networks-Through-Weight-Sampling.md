---
layout: post
title: "WSNet: Compact and Efficient Networks Through Weight Sampling"
date: 2018-05-22 13:41:19
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xiaojie Jin, Yingzhen Yang, Ning Xu, Jianchao Yang, Nebojsa Jojic, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach and a novel architecture, termed WSNet, for learning compact and efficient deep neural networks. Existing approaches conventionally learn full model parameters independently and then compress them via ad hoc processing such as model pruning or filter factorization. Alternatively, WSNet proposes learning model parameters by sampling from a compact set of learnable parameters, which naturally enforces {parameter sharing} throughout the learning process. We demonstrate that such a novel weight sampling approach (and induced WSNet) promotes both weights and computation sharing favorably. By employing this method, we can more efficiently learn much smaller networks with competitive performance compared to baseline networks with equal numbers of convolution filters. Specifically, we consider learning compact and efficient 1D convolutional neural networks for audio classification. Extensive experiments on multiple audio classification datasets verify the effectiveness of WSNet. Combined with weight quantization, the resulted models are up to 180 times smaller and theoretically up to 16 times faster than the well-established baselines, without noticeable performance drop.

##### Abstract (translated by Google)
我们提出了一种新的方法和一种称为WSNet的新型架构，用于学习紧凑和高效的深度神经网络。现有方法通常独立地学习完整模型参数，然后通过临时处理（例如模型修剪或过滤因子分解）对其进行压缩。或者，WSNet通过从一组紧密的可学习参数中抽样来提出学习模型参数，这在整个学习过程中自然地实施{参数共享}。我们证明这种新颖的权重抽样方法（和诱导WSNet）有利地促进了权重和计算共享。通过采用这种方法，与具有相同数量的卷积滤波器的基线网络相比，我们可以更有效地学习具有竞争性能的更小的网络。具体来说，我们考虑学习紧凑高效的一维卷积神经网络的音频分类。在多个音频分类数据集上的大量实验验证了WSNet的有效性。结合重量量化，结果模型比理想的基线快180倍，理论上速度快16倍，而且性能没有明显下降。

##### URL
[http://arxiv.org/abs/1711.10067](http://arxiv.org/abs/1711.10067)

##### PDF
[http://arxiv.org/pdf/1711.10067](http://arxiv.org/pdf/1711.10067)

