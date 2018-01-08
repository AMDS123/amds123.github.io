---
layout: post
title: "PixelLink: Detecting Scene Text via Instance Segmentation"
date: 2018-01-04 11:48:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Text_Classification Semantic_Segmentation Classification Deep_Learning Prediction Detection
author: Dan Deng, Haifeng Liu, Xuelong Li, Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
Most state-of-the-art scene text detection algorithms are deep learning based methods that depend on bounding box regression and perform at least two kinds of predictions: text/non-text classification and location regression. Regression plays a key role in the acquisition of bounding boxes in these methods, but it is not indispensable because text/non-text prediction can also be considered as a kind of semantic segmentation that contains full location information in itself. However, text instances in scene images often lie very close to each other, making them very difficult to separate via semantic segmentation. Therefore, instance segmentation is needed to address this problem. In this paper, PixelLink, a novel scene text detection algorithm based on instance segmentation, is proposed. Text instances are first segmented out by linking pixels within the same instance together. Text bounding boxes are then extracted directly from the segmentation result without location regression. Experiments show that, compared with regression-based methods, PixelLink can achieve better or comparable performance on several benchmarks, while requiring many fewer training iterations and less training data.

##### Abstract (translated by Google)
大多数最先进的场景文本检测算法是基于深度学习的方法，它依赖于边界框回归，并执行至少两种预测：文本/非文本分类和位置回归。回归在这些方法中边界框的获取中起着关键作用，但它并不是必不可少的，因为文本/非文本预测也可以被认为是一种包含完整位置信息的语义分割。然而，场景图像中的文本实例通常彼此非常接近，使得通过语义分割非常难以分离。因此，需要实例分段来解决这个问题。本文提出了一种基于实例分割的新型场景文本检测算法PixelLink。文本实例首先通过将同一实例内的像素链接在一起分割出来。然后直接从分割结果中提取文本边界框，而不进行位置回归。实验表明，与基于回归的方法相比，PixelLink可以在几个基准测试中获得更好或相当的性能，同时需要更少的训练迭代和更少的训练数据。

##### URL
[http://arxiv.org/abs/1801.01315](http://arxiv.org/abs/1801.01315)

##### PDF
[http://arxiv.org/pdf/1801.01315](http://arxiv.org/pdf/1801.01315)

