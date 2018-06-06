---
layout: post
title: "CFCM: Segmentation via Coarse to Fine Context Memory"
date: 2018-06-04 22:12:41
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN
author: Fausto Milletari, Nicola Rieke, Maximilian Baust, Marco Esposito, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Recent neural-network-based architectures for image segmentation make extensive usage of feature forwarding mechanisms to integrate information from multiple scales. Although yielding good results, even deeper architectures and alternative methods for feature fusion at different resolutions have been scarcely investigated for medical applications. In this work we propose to implement segmentation via an encoder-decoder architecture which differs from any other previously published method since (i) it employs a very deep architecture based on residual learning and (ii) combines features via a convolutional Long Short Term Memory (LSTM), instead of concatenation or summation. The intuition is that the memory mechanism implemented by LSTMs can better integrate features from different scales through a coarse-to-fine strategy; hence the name Coarse-to-Fine Context Memory (CFCM). We demonstrate the remarkable advantages of this approach on two datasets: the Montgomery county lung segmentation dataset, and the EndoVis 2015 challenge dataset for surgical instrument segmentation.

##### Abstract (translated by Google)
最近基于神经网络的图像分割架构广泛使用特征转发机制来整合来自多个尺度的信息。虽然产生了良好的结果，但对于医学应用来说，甚至更深层的体系结构和用于不同分辨率下的特征融合的替代方法已经很少被研究。在这项工作中，我们建议通过编码器 - 解码器架构来实现分割，该架构不同于任何其他先前公开的方法，因为（i）它采用基于残差学习的非常深的架构和（ii）通过卷积长短期存储器LSTM），而不是拼接或求和。直觉是，LSTMs实现的内存机制可以通过粗放到精细的策略更好地集成不同尺度的特征;因此称为粗至细上下文存储器（CFCM）。我们证明了这种方法在两个数据集上的显着优势：蒙哥马利县肺部分割数据集和用于手术器械分割的EndoVis 2015挑战数据集。

##### URL
[http://arxiv.org/abs/1806.01413](http://arxiv.org/abs/1806.01413)

##### PDF
[http://arxiv.org/pdf/1806.01413](http://arxiv.org/pdf/1806.01413)

