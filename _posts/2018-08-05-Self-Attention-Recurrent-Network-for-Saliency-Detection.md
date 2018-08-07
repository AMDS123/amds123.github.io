---
layout: post
title: "Self-Attention Recurrent Network for Saliency Detection"
date: 2018-08-05 15:31:22
categories: arXiv_CV
tags: arXiv_CV Salient Attention Detection
author: Fengdong Sun, Wenhui Li, Yuanyuan Guan
mathjax: true
---

* content
{:toc}

##### Abstract
Feature maps in deep neural network generally contain different semantics. Existing methods often omit their characteristics that may lead to sub-optimal results. In this paper, we propose a novel end-to-end deep saliency network which could effectively utilize multi-scale feature maps according to their characteristics. Shallow layers often contain more local information, and deep layers have advantages in global semantics. Therefore, the network generates elaborate saliency maps by enhancing local and global information of feature maps in different layers. On one hand, local information of shallow layers is enhanced by a recurrent structure which shared convolution kernel at different time steps. On the other hand, global information of deep layers is utilized by a self-attention module, which generates different attention weights for salient objects and backgrounds thus achieve better performance. Experimental results on four widely used datasets demonstrate that our method has advantages in performance over existing algorithms.

##### Abstract (translated by Google)
深度神经网络中的特征映射通常包含不同的语义。现有方法通常省略其可能导致次优结果的特征。在本文中，我们提出了一种新颖的端到端深度显着网络，可以根据其特点有效地利用多尺度特征图。浅层通常包含更多本地信息，深层在全局语义中具有优势。因此，网络通过增强不同层中的特征地图的局部和全局信息来生成精细的显着性地图。一方面，通过在不同时间步长共享卷积核的循环结构来增强浅层的局部信息。另一方面，自我关注模块利用深层的全局信息，其为显着对象和背景产生不同的注意权重，从而实现更好的性能。四个广泛使用的数据集的实验结果表明，我们的方法在性能上优于现有算法。

##### URL
[https://arxiv.org/abs/1808.01634](https://arxiv.org/abs/1808.01634)

##### PDF
[https://arxiv.org/pdf/1808.01634](https://arxiv.org/pdf/1808.01634)

