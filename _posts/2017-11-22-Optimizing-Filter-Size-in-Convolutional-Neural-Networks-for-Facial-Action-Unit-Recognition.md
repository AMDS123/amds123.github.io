---
layout: post
title: "Optimizing Filter Size in Convolutional Neural Networks for Facial Action Unit Recognition"
date: 2017-11-22 19:33:09
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Shizhong Han, Zibo Meng, Zhiyuan Li, James O'Reilly, Jie Cai, Xiaofeng Wang, Yan Tong
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing facial action units (AUs) during spontaneous facial displays is a challenging problem. Most recently, Convolutional Neural Networks (CNNs) have shown promise for facial AU recognition, where predefined and fixed convolution filter sizes are employed. In order to achieve the best performance, the optimal filter size is often empirically found by conducting extensive experimental validation. Such a training process suffers from expensive training cost, especially as the network becomes deeper. This paper proposes a novel Optimized Filter Size CNN (OFS-CNN), where the filter sizes and weights of all convolutional layers are learned simultaneously from the training data along with learning convolution filters. Specifically, the filter size is defined as a continuous variable, which is optimized by minimizing the training loss. Experimental results on two AU-coded spontaneous databases have shown that the proposed OFS-CNN is capable of estimating optimal filter size for varying image resolution and outperforms traditional CNNs with the best filter size obtained by exhaustive search. The OFS-CNN also beats the CNN using multiple filter sizes and more importantly, is much more efficient during testing with the proposed forward-backward propagation algorithm.

##### Abstract (translated by Google)
在自发面部显示期间识别面部动作单元（AU）是一个具有挑战性的问题。最近，卷积神经网络（CNN）已经显示了对面部AU识别的承诺，其中使用了预定义的和固定的卷积滤波器大小。为了达到最佳的性能，通过进行大量的实验验证，最佳的过滤器尺寸通常是经验性的。这样的训练过程遭受了昂贵的训练成本，尤其是随着网络变得更深。本文提出了一种新颖的优化滤波器大小CNN（OFS-CNN），其中所有卷积层的滤波器大小和权重通过学习卷积滤波器同时从训练数据中学习。具体而言，过滤器大小被定义为连续变量，通过最小化训练损失来优化过滤器大小。在两个AU编码的自发数据库上的实验结果表明，所提出的OFS-CNN能够估计用于变化的图像分辨率的最佳滤波器大小，并且通过穷尽搜索获得最佳滤波器大小的传统CNN。 OFS-CNN也使用多个滤波器大小击败CNN，更重要的是，在所提出的前向 - 后向传播算法的测试中效率更高。

##### URL
[https://arxiv.org/abs/1707.08630](https://arxiv.org/abs/1707.08630)

##### PDF
[https://arxiv.org/pdf/1707.08630](https://arxiv.org/pdf/1707.08630)

