---
layout: post
title: "Full-Resolution Residual Networks for Semantic Segmentation in Street Scenes"
date: 2016-12-06 19:36:19
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Recognition
author: Tobias Pohlen, Alexander Hermans, Markus Mathias, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image segmentation is an essential component of modern autonomous driving systems, as an accurate understanding of the surrounding scene is crucial to navigation and action planning. Current state-of-the-art approaches in semantic image segmentation rely on pre-trained networks that were initially developed for classifying images as a whole. While these networks exhibit outstanding recognition performance (i.e., what is visible?), they lack localization accuracy (i.e., where precisely is something located?). Therefore, additional processing steps have to be performed in order to obtain pixel-accurate segmentation masks at the full image resolution. To alleviate this problem we propose a novel ResNet-like architecture that exhibits strong localization and recognition performance. We combine multi-scale context with pixel-level accuracy by using two processing streams within our network: One stream carries information at the full image resolution, enabling precise adherence to segment boundaries. The other stream undergoes a sequence of pooling operations to obtain robust features for recognition. The two streams are coupled at the full image resolution using residuals. Without additional processing steps and without pre-training, our approach achieves an intersection-over-union score of 71.8% on the Cityscapes dataset.

##### Abstract (translated by Google)
语义图像分割是现代自动驾驶系统的重要组成部分，因为对周围场景的精确理解对导航和行动规划至关重要。当前在语义图像分割中的最先进的方法依赖于最初开发用于将图像分类为整体的预先训练的网络。尽管这些网络表现出出色的识别性能（即可见性），但是它们缺乏定位准确性（即精确定位的位置？）。因此，为了以全图像分辨率获得像素精确的分割掩模，必须执行额外的处理步骤。为了缓解这个问题，我们提出了一种新的ResNet类架构，展现出强大的本地化和识别性能。我们通过在网络中使用两个处理流，将多尺度上下文与像素级准确性结合在一起：一个数据流以全图像分辨率传输信息，从而可以精确地遵守分割边界。另一个流经历一系列池操作以获得用于识别的强健特征。这两个流在使用残差的全图像分辨率下耦合。没有额外的处理步骤，也没有预先训练，我们的方法在Cityscapes数据集上达到了71.8％的交汇比分数。

##### URL
[https://arxiv.org/abs/1611.08323](https://arxiv.org/abs/1611.08323)

##### PDF
[https://arxiv.org/pdf/1611.08323](https://arxiv.org/pdf/1611.08323)

