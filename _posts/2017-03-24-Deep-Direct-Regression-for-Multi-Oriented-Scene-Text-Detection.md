---
layout: post
title: "Deep Direct Regression for Multi-Oriented Scene Text Detection"
date: 2017-03-24 05:54:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Wenhao He, Xu-Yao Zhang, Fei Yin, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we first provide a new perspective to divide existing high performance object detection methods into direct and indirect regressions. Direct regression performs boundary regression by predicting the offsets from a given point, while indirect regression predicts the offsets from some bounding box proposals. Then we analyze the drawbacks of the indirect regression, which the recent state-of-the-art detection structures like Faster-RCNN and SSD follows, for multi-oriented scene text detection, and point out the potential superiority of direct regression. To verify this point of view, we propose a deep direct regression based method for multi-oriented scene text detection. Our detection framework is simple and effective with a fully convolutional network and one-step post processing. The fully convolutional network is optimized in an end-to-end way and has bi-task outputs where one is pixel-wise classification between text and non-text, and the other is direct regression to determine the vertex coordinates of quadrilateral text boundaries. The proposed method is particularly beneficial for localizing incidental scene texts. On the ICDAR2015 Incidental Scene Text benchmark, our method achieves the F1-measure of 81%, which is a new state-of-the-art and significantly outperforms previous approaches. On other standard datasets with focused scene texts, our method also reaches the state-of-the-art performance.

##### Abstract (translated by Google)
在本文中，我们首先提供一个新的视角，将现有的高性能对象检测方法分为直接和间接回归。直接回归通过预测来自给定点的偏移来执行边界回归，而间接回归则预测来自某些边界框提议的偏移。然后分析了Faster-RCNN和SSD等最新的检测结构对多方向场景文本检测的间接回归的缺陷，指出了直接回归的潜在优越性。为了验证这个观点，我们提出了一种基于深度直接回归的多方向场景文本检测方法。我们的检测框架是完全卷积网络和一步后处理简单而有效的。完全卷积网络以端到端的方式进行了优化，并且具有双任务输出，其中一个是文本与非文本之间的按像素分类，另一个是直接回归以确定四边形文本边界的顶点坐标。所提出的方法对于定位附带的场景文本是特别有益的。在ICDAR2015杂志场景文本基准测试中，我们的方法达到了81％的F1-度量，这是一个新的技术水平，明显优于以前的方法。在其他具有重点场景文本的标准数据集上，我们的方法也达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1703.08289](https://arxiv.org/abs/1703.08289)

##### PDF
[https://arxiv.org/pdf/1703.08289](https://arxiv.org/pdf/1703.08289)

