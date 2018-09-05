---
layout: post
title: "Regularizing Deep Hashing Networks Using GAN Generated Fake Images"
date: 2018-09-02 16:24:44
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
最近，基于深度网络的散列（深度散列）已成为大规模图像检索的主要方法。它旨在通过深度网络学习图像的紧凑按位表示，以便将类似的图像映射到附近的哈希码。由于深度网络模型通常具有大量参数，因此对于我们的训练数据来说可能过于复杂，导致模型过度拟合。为了解决这个问题，在本文中，我们提出了一个简单的两阶段管道来学习深度哈希模型，通过使用伪图像规范深度哈希网络。第一阶段是通过生成对抗网络（GAN）从原始训练集生成假图像而无需额外数据。在第二阶段，我们提出了一个深层架构来学习哈希函数，其中我们使用基于最大熵的损失来合并GAN新创建的伪图像。我们通过惩罚低熵输出哈希码表明这种损失是深层架构的强有力的正则化器。这种损失也可以被解释为模型集合，通过同时训练许多具有大量权重共享但在不同训练集上的网络模型。几个基准数据集的经验评估结果表明，与最先进的散列方法相比，所提出的方法具有更好的性能。

##### URL
[http://arxiv.org/abs/1803.09466](http://arxiv.org/abs/1803.09466)

##### PDF
[http://arxiv.org/e-print/1803.09466](http://arxiv.org/e-print/1803.09466)

