---
layout: post
title: "Efficient piecewise training of deep structured models for semantic segmentation"
date: 2016-06-06 00:26:44
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Relation
author: Guosheng Lin, Chunhua Shen, Anton van dan Hengel, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in semantic image segmentation have mostly been achieved by training deep convolutional neural networks (CNNs). We show how to improve semantic segmentation through the use of contextual information; specifically, we explore `patch-patch' context between image regions, and `patch-background' context. For learning from the patch-patch context, we formulate Conditional Random Fields (CRFs) with CNN-based pairwise potential functions to capture semantic correlations between neighboring patches. Efficient piecewise training of the proposed deep structured model is then applied to avoid repeated expensive CRF inference for back propagation. For capturing the patch-background context, we show that a network design with traditional multi-scale image input and sliding pyramid pooling is effective for improving performance. Our experimental results set new state-of-the-art performance on a number of popular semantic segmentation datasets, including NYUDv2, PASCAL VOC 2012, PASCAL-Context, and SIFT-flow. In particular, we achieve an intersection-over-union score of 78.0 on the challenging PASCAL VOC 2012 dataset.

##### Abstract (translated by Google)
语义图像分割的最新进展主要是通过训练深度卷积神经网络（CNN）来实现的。我们展示了如何通过使用上下文信息来改善语义分割。具体来说，我们探讨了图像区域之间的“patch-patch”上下文，以及“patch-background”上下文。为了从补丁上下文中学习，我们用基于CNN的成对潜在函数来制定条件随机场（CRF），以捕获相邻补丁之间的语义相关性。然后应用所提出的深层结构化模型的有效分段训练以避免重复的昂贵的CRF推断来反向传播。为了捕捉补丁背景的情况，我们表明，具有传统的多尺度图像输入和滑动金字塔池的网络设计对于提高性能是有效的。我们的实验结果为许多流行的语义分割数据集（包括NYUDv2，PASCAL VOC 2012，PASCAL-Context和SIFT流）设置了最新的最新性能。具体而言，我们在具有挑战性的PASCAL VOC 2012数据集上获得了78.0的交汇分数。

##### URL
[https://arxiv.org/abs/1504.01013](https://arxiv.org/abs/1504.01013)

##### PDF
[https://arxiv.org/pdf/1504.01013](https://arxiv.org/pdf/1504.01013)

