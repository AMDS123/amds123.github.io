---
layout: post
title: "Learning a Discriminative Null Space for Person Re-identification"
date: 2016-03-07 16:26:07
categories: arXiv_CV
tags: arXiv_CV Re-identification Face Person_Re-identification
author: Li Zhang, Tao Xiang, Shaogang Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing person re-identification (re-id) methods focus on learning the optimal distance metrics across camera views. Typically a person's appearance is represented using features of thousands of dimensions, whilst only hundreds of training samples are available due to the difficulties in collecting matched training images. With the number of training samples much smaller than the feature dimension, the existing methods thus face the classic small sample size (SSS) problem and have to resort to dimensionality reduction techniques and/or matrix regularisation, which lead to loss of discriminative power. In this work, we propose to overcome the SSS problem in re-id distance metric learning by matching people in a discriminative null space of the training data. In this null space, images of the same person are collapsed into a single point thus minimising the within-class scatter to the extreme and maximising the relative between-class separation simultaneously. Importantly, it has a fixed dimension, a closed-form solution and is very efficient to compute. Extensive experiments carried out on five person re-identification benchmarks including VIPeR, PRID2011, CUHK01, CUHK03 and Market1501 show that such a simple approach beats the state-of-the-art alternatives, often by a big margin.

##### Abstract (translated by Google)
大多数现有的人重新识别（re-id）方法的重点在于学习跨摄像机视图的最佳距离度量。典型情况下，一个人的外表是使用数千个维度的特征表示的，而由于难以收集匹配的训练图像，只有数百个训练样本可用。与训练样本比特征尺寸小得多的数量，现有的方法因此面临的经典小样本（SSS）的问题，不得不求助于降维的技术和/或基质正则化，从而导致辨别力的损失。在这项工作中，我们提出通过在训练数据的一个有区别的零空间中匹配人来克服重复距离度量学习中的SSS问题。在这个零空间中，同一个人的图像被折叠成一个点，从而将类内分散最小化到极端，同时最大化相对的类间分离。重要的是，它有一个固定的维度，一个封闭的解决方案，并且是非常有效的计算。包括VIPeR，PRID2011，CUHK01，CUHK03和Market1501在内的五个人重新识别基准进行了大量的实验，表明这样一个简单的方法往往会大幅度地超越最新的替代方案。

##### URL
[https://arxiv.org/abs/1603.02139](https://arxiv.org/abs/1603.02139)

##### PDF
[https://arxiv.org/pdf/1603.02139](https://arxiv.org/pdf/1603.02139)

