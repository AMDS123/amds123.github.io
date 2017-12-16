---
layout: post
title: "Dynamic Steerable Blocks in Deep Residual Networks"
date: 2017-07-19 15:12:52
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Segmentation CNN Inference Detection
author: Jörn-Henrik Jacobsen, Bert de Brabandere, Arnold W.M. Smeulders
mathjax: true
---

* content
{:toc}

##### Abstract
Filters in convolutional networks are typically parameterized in a pixel basis, that does not take prior knowledge about the visual world into account. We investigate the generalized notion of frames designed with image properties in mind, as alternatives to this parametrization. We show that frame-based ResNets and Densenets can improve performance on Cifar-10+ consistently, while having additional pleasant properties like steerability. By exploiting these transformation properties explicitly, we arrive at dynamic steerable blocks. They are an extension of residual blocks, that are able to seamlessly transform filters under pre-defined transformations, conditioned on the input at training and inference time. Dynamic steerable blocks learn the degree of invariance from data and locally adapt filters, allowing them to apply a different geometrical variant of the same filter to each location of the feature map. When evaluated on the Berkeley Segmentation contour detection dataset, our approach outperforms all competing approaches that do not utilize pre-training. Our results highlight the benefits of image-based regularization to deep networks.

##### Abstract (translated by Google)
卷积网络中的滤波器通常以像素为基础进行参数化，不考虑视觉世界的先验知识。我们研究了设计有图像属性的框架的广义概念，作为这种参数化的替代方案。我们显示基于帧的ResNets和Densenets可以一致地改进Cifar-10 +的性能，同时还具有其他令人愉快的特性，如可控性。通过明确地利用这些转换属性，我们到达了动态可控块。它们是残差块的扩展，能够在预定义的变换下无缝地变换滤波器，以训练和推理时间的输入为条件。动态可控块从数据中学习不变程度，并在本地调整过滤器，使他们能够将相同过滤器的不同几何变体应用到特征映射的每个位置。当在伯克利分割轮廓检测数据集上评估时，我们的方法胜过所有不使用预培训的竞争方法。我们的结果突出了基于图像的正则化对深度网络的好处。

##### URL
[https://arxiv.org/abs/1706.00598](https://arxiv.org/abs/1706.00598)

##### PDF
[https://arxiv.org/pdf/1706.00598](https://arxiv.org/pdf/1706.00598)

