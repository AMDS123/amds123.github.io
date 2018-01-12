---
layout: post
title: "Segment-based Methods for Facial Attribute Detection from Partial Faces"
date: 2018-01-10 20:32:35
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction Detection
author: Upal Mahbub, Sayantan Sarkar, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods of attribute detection from faces almost always assume the presence of a full, unoccluded face. Hence, their performance degrades for partially visible and occluded faces. In this paper, we introduce SPLITFACE, a deep convolutional neural network-based method that is explicitly designed to perform attribute detection in partially occluded faces. Taking several facial segments and the full face as input, the proposed method takes a data driven approach to determine which attributes are localized in which facial segments. The unique architecture of the network allows each attribute to be predicted by multiple segments, which permits the implementation of committee machine techniques for combining local and global decisions to boost performance. With access to segment-based predictions, SPLITFACE can predict well those attributes which are localized in the visible parts of the face, without having to rely on the presence of the whole face. We use the CelebA and LFWA facial attribute datasets for standard evaluations. We also modify both datasets, to occlude the faces, so that we can evaluate the performance of attribute detection algorithms on partial faces. Our evaluation shows that SPLITFACE significantly outperforms other recent methods especially for partial faces.

##### Abstract (translated by Google)
从面部检测属性的最先进的方法几乎总是假定存在完整的，不被遮挡的面部。因此，他们的表现降低部分可见和闭塞的面孔。在本文中，我们介绍了一种基于深度卷积神经网络的SPLITFACE方法，该方法被明确设计用于在部分遮挡面部进行属性检测。以多个面部片段和全脸作为输入，所提出的方法采用数据驱动的方法来确定哪些属性在哪个面部片段中定位。网络的独特架构允许每个属性由多个部分预测，这允许实施委员会机器技术来结合本地和全球决策来提高性能。通过访问基于细分的预测，SPLITFACE可以很好地预测位于脸部可见部分的那些属性，而不必依赖整个脸部的存在。我们使用CelebA和LFWA面部属性数据集进行标准评估。我们也修改这两个数据集，以遮挡面部，以便我们可以评估属性检测算法在部分面上的性能。我们的评估显示，SPLITFACE明显优于其他近期的方法，特别是对于局部人脸。

##### URL
[http://arxiv.org/abs/1801.03546](http://arxiv.org/abs/1801.03546)

##### PDF
[http://arxiv.org/pdf/1801.03546](http://arxiv.org/pdf/1801.03546)

