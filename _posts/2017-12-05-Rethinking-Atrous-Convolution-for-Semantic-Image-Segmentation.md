---
layout: post
title: 'Rethinking Atrous Convolution for Semantic Image Segmentation'
date: 2017-12-05 18:06:21
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Liang-Chieh Chen, George Papandreou, Florian Schroff, Hartwig Adam
---

* content
{:toc}

##### Abstract
In this work, we revisit atrous convolution, a powerful tool to explicitly adjust filter's field-of-view as well as control the resolution of feature responses computed by Deep Convolutional Neural Networks, in the application of semantic image segmentation. To handle the problem of segmenting objects at multiple scales, we design modules which employ atrous convolution in cascade or in parallel to capture multi-scale context by adopting multiple atrous rates. Furthermore, we propose to augment our previously proposed Atrous Spatial Pyramid Pooling module, which probes convolutional features at multiple scales, with image-level features encoding global context and further boost performance. We also elaborate on implementation details and share our experience on training our system. The proposed `DeepLabv3' system significantly improves over our previous DeepLab versions without DenseCRF post-processing and attains comparable performance with other state-of-art models on the PASCAL VOC 2012 semantic image segmentation benchmark.

##### Abstract (translated by Google)
在这项工作中，我们重新讨论了积累的卷积，这是一个强大的工具来显式调整过滤器的视野，以及控制深度卷积神经网络计算的特征响应的分辨率在语义图像分割的应用。为了解决多尺度下对象分割的问题，我们设计了采用级联或并行卷积的卷积模块，采用多种速率来捕获多尺度上下文。此外，我们建议增加我们先前提出的Atrous空间金字塔合并模块，该模块可以在多个尺度上探测卷积特征，并具有编码全局上下文的图像级特征，并进一步提升性能。我们还详细介绍实施细节，分享我们培训系统的经验。所提议的“DeepLabv3”系统比我们以前的DeepLab版本在没有DenseCRF后处理的情况下显着提高，并且在PASCAL VOC 2012语义图像分割基准测试中获得了与其他最先进的模型相当的性能。

##### URL
[http://arxiv.org/abs/1706.05587](http://arxiv.org/abs/1706.05587)

