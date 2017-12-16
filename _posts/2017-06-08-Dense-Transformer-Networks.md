---
layout: post
title: "Dense Transformer Networks"
date: 2017-06-08 00:10:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Prediction
author: Jun Li, Yongjun Chen, Lei Cai, Ian Davidson, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
The key idea of current deep learning methods for dense prediction is to apply a model on a regular patch centered on each pixel to make pixel-wise predictions. These methods are limited in the sense that the patches are determined by network architecture instead of learned from data. In this work, we propose the dense transformer networks, which can learn the shapes and sizes of patches from data. The dense transformer networks employ an encoder-decoder architecture, and a pair of dense transformer modules are inserted into each of the encoder and decoder paths. The novelty of this work is that we provide technical solutions for learning the shapes and sizes of patches from data and efficiently restoring the spatial correspondence required for dense prediction. The proposed dense transformer modules are differentiable, thus the entire network can be trained. We apply the proposed networks on natural and biological image segmentation tasks and show superior performance is achieved in comparison to baseline methods.

##### Abstract (translated by Google)
密集预测的当前深度学习方法的关键思想是在以每个像素为中心的规则块上应用模型以进行像素方式的预测。这些方法是有限的，因为补丁是由网络架构决定的，而不是从数据中学习的。在这项工作中，我们提出了密集的变压器网络，它可以从数据中学习补丁的形状和大小。密集变压器网络使用编码器 - 解码器架构，并且一对密集变压器模块被插入到编码器和解码器路径中的每一个中。这项工作的新颖之处在于我们提供了从数据中学习补丁的形状和大小的技术解决方案，并有效地恢复密集预测所需的空间对应。所提出的密集变压器模块是可微分的，因此可以训练整个网络。我们将所提议的网络应用于自然和生物图像分割任务，并且与基线方法相比，显示出优越的性能。

##### URL
[https://arxiv.org/abs/1705.08881](https://arxiv.org/abs/1705.08881)

##### PDF
[https://arxiv.org/pdf/1705.08881](https://arxiv.org/pdf/1705.08881)

