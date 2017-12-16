---
layout: post
title: "RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation"
date: 2016-11-25 02:01:05
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Prediction Recognition
author: Guosheng Lin, Anton Milan, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, very deep convolutional neural networks (CNNs) have shown outstanding performance in object recognition and have also been the first choice for dense classification problems such as semantic segmentation. However, repeated subsampling operations like pooling or convolution striding in deep CNNs lead to a significant decrease in the initial image resolution. Here, we present RefineNet, a generic multi-path refinement network that explicitly exploits all the information available along the down-sampling process to enable high-resolution prediction using long-range residual connections. In this way, the deeper layers that capture high-level semantic features can be directly refined using fine-grained features from earlier convolutions. The individual components of RefineNet employ residual connections following the identity mapping mindset, which allows for effective end-to-end training. Further, we introduce chained residual pooling, which captures rich background context in an efficient manner. We carry out comprehensive experiments and set new state-of-the-art results on seven public datasets. In particular, we achieve an intersection-over-union score of 83.4 on the challenging PASCAL VOC 2012 dataset, which is the best reported result to date.

##### Abstract (translated by Google)
最近，非常深的卷积神经网络（CNN）在目标识别方面表现出色，也成为语义分割等密集分类问题的首选。然而，重复的子采样操作，如深度CNN中的汇集或卷积步进导致初始图像分辨率的显着下降。在这里，我们介绍一个通用的多路径优化网络RefineNet，它明确地利用了下采样过程中可用的所有信息，以使用远程剩余连接实现高分辨率预测。通过这种方式，捕获高级语义特征的更深层可以使用早期卷积的细粒度特征直接细化。 RefineNet的各个组件使用身份映射思维模式下的剩余连接，从而实现有效的端到端培训。此外，我们引入链式残差池，以高效的方式捕获丰富的背景上下文。我们进行了全面的实验，并在七个公共数据集上设置了最新的最新成果。特别是，我们在具有挑战性的PASCAL VOC 2012数据集上获得了83.4的交叉点整合得分，这是迄今为止报告的最好结果。

##### URL
[https://arxiv.org/abs/1611.06612](https://arxiv.org/abs/1611.06612)

##### PDF
[https://arxiv.org/pdf/1611.06612](https://arxiv.org/pdf/1611.06612)

