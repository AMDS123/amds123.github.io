---
layout: post
title: "Regularizing Deep Hashing Networks Using GAN Generated Fake Images"
date: 2018-03-26 08:30:18
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Adversarial GAN
author: Libing Geng, Yan Pan, Jikai Chen, Hanjiang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep-networks-based hashing (deep hashing) has become a leading approach for large-scale image retrieval. It aims to learn a compact bitwise representation for images via deep networks, so that similar images are mapped to nearby hash codes. Since a deep network model usually has a large number of parameters, it may probably be too complicated for the training data we have, leading to model over-fitting. To address this issue, in this paper, we propose a simple two-stage pipeline to learn deep hashing models, by regularizing the deep hashing networks using fake images. The first stage is to generate fake images from the original training set without extra data, via a generative adversarial network (GAN). In the second stage, we propose a deep architec- ture to learn hash functions, in which we use a maximum-entropy based loss to incorporate the newly created fake images by the GAN. We show that this loss acts as a strong regularizer of the deep architecture, by penalizing low-entropy output hash codes. This loss can also be interpreted as a model ensemble by simultaneously training many network models with massive weight sharing but over different training sets. Empirical evaluation results on several benchmark datasets show that the proposed method has superior performance gains over state-of-the-art hashing methods.

##### Abstract (translated by Google)
最近，基于深度网络的哈希（深度哈希）已成为大规模图像检索的主要方法。它旨在通过深度网络学习图像的紧凑按位表示，以便将类似图像映射到附近的哈希代码。由于深度网络模型通常具有大量参数，因此对于我们的训练数据可能太复杂，导致模型过度拟合。为了解决这个问题，在本文中，我们提出了一个简单的两阶段流水线来学习深度哈希模型，通过使用假图像对深度哈希网络进行规则化。第一阶段是通过生成对抗网络（GAN）从原始训练集合生成假图像，而不需要额外的数据。在第二阶段，我们提出了一个深入的结构来学习散列函数，其中我们使用基于最大熵的损失来整合由GAN新创建的假图像。我们通过惩罚低熵输出哈希码来证明这种损失作为深层架构的强大正规化者。这种损失也可以通过同时训练许多网络模型与大量的权重分享，但在不同的训练集上解释为模型整体。对几个基准数据集的实证评估结果表明，所提出的方法比现有技术的散列方法具有更高的性能收益。

##### URL
[https://arxiv.org/abs/1803.09466](https://arxiv.org/abs/1803.09466)

##### PDF
[https://arxiv.org/pdf/1803.09466](https://arxiv.org/pdf/1803.09466)

