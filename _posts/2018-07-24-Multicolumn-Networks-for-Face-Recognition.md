---
layout: post
title: "Multicolumn Networks for Face Recognition"
date: 2018-07-24 15:45:58
categories: arXiv_CV
tags: arXiv_CV Face Classification Recognition Face_Recognition
author: Weidi Xie, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of this work is set-based face recognition, i.e. to decide if two sets of images of a face are of the same person or not. Conventionally, the set-wise feature descriptor is computed as an average of the descriptors from individual face images within the set. In this paper, we design a neural network architecture that learns to aggregate based on both "visual" quality (resolution, illumination), and "content" quality (relative importance for discriminative classification). To this end, we propose a Multicolumn Network (MN) that takes a set of images (the number in the set can vary) as input, and learns to compute a fix-sized feature descriptor for the entire set. To encourage high-quality representations, each individual input image is first weighted by its "visual" quality, determined by a self-quality assessment module, and followed by a dynamic recalibration based on "content" qualities relative to the other images within the set. Both of these qualities are learnt implicitly during training for set-wise classification. Comparing with the previous state-of-the-art architectures trained with the same dataset (VGGFace2), our Multicolumn Networks show an improvement of between 2-6% on the IARPA IJB face recognition benchmarks, and exceed the state of the art for all methods on these benchmarks.

##### Abstract (translated by Google)
这项工作的目的是基于集合的面部识别，即确定一组面部的两组图像是否属于同一个人。传统上，逐集特征描述符被计算为来自集合内的各个面部图像的描述符的平均值。在本文中，我们设计了一种神经网络架构，该架构学习基于“视觉”质量（分辨率，照明）和“内容”质量（判别分类的相对重要性）进行聚合。为此，我们提出了一种多列网络（MN），它将一组图像（集合中的数字可以变化）作为输入，并学习计算整个集合的固定大小的特征描述符。为了鼓励高质量的表示，每个单独的输入图像首先通过其“视觉”质量加权，由自我质量评估模块确定，然后基于相对于集合内其他图像的“内容”质量进行动态重新校准。 。在集训分类培训期间，这两种品质都是隐含的。与先前使用相同数据集（VGGFace2）培训的最先进架构相比，我们的多柱网络在IARPA IJB人脸识别基准测试中显示出2-6％的改进，并且超过了所有人的最新技术水平。这些基准的方法。

##### URL
[https://arxiv.org/abs/1807.09192](https://arxiv.org/abs/1807.09192)

##### PDF
[https://arxiv.org/pdf/1807.09192](https://arxiv.org/pdf/1807.09192)

