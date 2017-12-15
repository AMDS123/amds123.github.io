---
layout: post
title: "Systematic evaluation of CNN advances on the ImageNet"
date: 2016-06-13 13:48:39
categories: arXiv_CV
tags: arXiv_CV CNN
author: Dmytro Mishkin, Nikolay Sergievskiy, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
The paper systematically studies the impact of a range of recent advances in CNN architectures and learning methods on the object categorization (ILSVRC) problem. The evalution tests the influence of the following choices of the architecture: non-linearity (ReLU, ELU, maxout, compatibility with batch normalization), pooling variants (stochastic, max, average, mixed), network width, classifier design (convolutional, fully-connected, SPP), image pre-processing, and of learning parameters: learning rate, batch size, cleanliness of the data, etc. The performance gains of the proposed modifications are first tested individually and then in combination. The sum of individual gains is bigger than the observed improvement when all modifications are introduced, but the "deficit" is small suggesting independence of their benefits. We show that the use of 128x128 pixel images is sufficient to make qualitative conclusions about optimal network structure that hold for the full size Caffe and VGG nets. The results are obtained an order of magnitude faster than with the standard 224 pixel images.

##### Abstract (translated by Google)
本文系统地研究了CNN架构和学习方法在目标分类（ILSVRC）问题上的一系列最新进展的影响。评估测试了以下架构选择的影响：非线性（ReLU，ELU，maxout，批量标准化的兼容性），池化变量（随机，最大，平均，混合），网络宽度，分类器设计（卷积，完全SPP），图像预处理以及学习参数：学习速率，批量大小，数据的清洁度等。所提出的修改的性能增益首先被单独测试，然后结合使用。在引入所有修改后，个人收益的总和大于观察到的改善，但是“赤字”很小，表明它们的利益是独立的。我们表明，使用128x128像素的图像足以作出关于最佳网络结构的定性结论，适用于全尺寸Caffe和VGG网络。结果比标准的224像素图像快一个数量级。

##### URL
[https://arxiv.org/abs/1606.02228](https://arxiv.org/abs/1606.02228)

##### PDF
[https://arxiv.org/pdf/1606.02228](https://arxiv.org/pdf/1606.02228)

