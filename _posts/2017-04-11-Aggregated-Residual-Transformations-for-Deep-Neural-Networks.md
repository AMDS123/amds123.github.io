---
layout: post
title: "Aggregated Residual Transformations for Deep Neural Networks"
date: 2017-04-11 01:53:41
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Detection
author: Saining Xie, Ross Girshick, Piotr Dollár, Zhuowen Tu, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple, highly modularized network architecture for image classification. Our network is constructed by repeating a building block that aggregates a set of transformations with the same topology. Our simple design results in a homogeneous, multi-branch architecture that has only a few hyper-parameters to set. This strategy exposes a new dimension, which we call "cardinality" (the size of the set of transformations), as an essential factor in addition to the dimensions of depth and width. On the ImageNet-1K dataset, we empirically show that even under the restricted condition of maintaining complexity, increasing cardinality is able to improve classification accuracy. Moreover, increasing cardinality is more effective than going deeper or wider when we increase the capacity. Our models, named ResNeXt, are the foundations of our entry to the ILSVRC 2016 classification task in which we secured 2nd place. We further investigate ResNeXt on an ImageNet-5K set and the COCO detection set, also showing better results than its ResNet counterpart. The code and models are publicly available online.

##### Abstract (translated by Google)
我们提出了一个简单的，高度模块化的图像分类网络架构。我们的网络是通过重复构建一个具有相同拓扑的转换集合的构建块来构建的。我们的简单设计产生了一个同构的多分支体系结构，只有一些超参数可供设置。这个策略揭示了一个新的维度，我们称之为“基数”（这组变量的大小），除了深度和宽度之外还是一个重要的因素。在ImageNet-1K数据集上，我们凭经验证明，即使在维持复杂度的限制条件下，增加基数也能提高分类精度。而且，增加基数比增加容量时更深更宽。我们的模型名为ResNeXt，是我们进入ILSVRC 2016分类任务的基础，我们获得了第二名。我们进一步研究了ImageNet-5K集合和COCO检测集合上的ResNeXt，也显示出比ResNet更好的结果。代码和模型在线公开。

##### URL
[https://arxiv.org/abs/1611.05431](https://arxiv.org/abs/1611.05431)

##### PDF
[https://arxiv.org/pdf/1611.05431](https://arxiv.org/pdf/1611.05431)

