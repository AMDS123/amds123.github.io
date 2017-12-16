---
layout: post
title: "Deep Hashing with Triplet Quantization Loss"
date: 2017-10-31 13:08:42
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Yuefu Zhou, Shanshan Huang, Ya Zhang, Yanfeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the explosive growth of image databases, deep hashing, which learns compact binary descriptors for images, has become critical for fast image retrieval. Many existing deep hashing methods leverage quantization loss, defined as distance between the features before and after quantization, to reduce the error from binarizing features. While minimizing the quantization loss guarantees that quantization has minimal effect on retrieval accuracy, it unfortunately significantly reduces the expressiveness of features even before the quantization. In this paper, we show that the above definition of quantization loss is too restricted and in fact not necessary for maintaining high retrieval accuracy. We therefore propose a new form of quantization loss measured in triplets. The core idea of the triplet quantization loss is to learn discriminative real-valued descriptors which lead to minimal loss on retrieval accuracy after quantization. Extensive experiments on two widely used benchmark data sets of different scales, CIFAR-10 and In-shop, demonstrate that the proposed method outperforms the state-of-the-art deep hashing methods. Moreover, we show that the compact binary descriptors obtained with triplet quantization loss lead to very small performance drop after quantization.

##### Abstract (translated by Google)
随着图像数据库的爆炸性增长，为图像学习紧凑的二进制描述符的深度哈希已经成为快速图像检索的关键。许多现有的深度哈希方法利用量化损失（定义为量化之前和之后的特征之间的距离）来减少二值化特征的误差。尽管最小化量化损失保证了量化对检索精度的影响最小，但是不幸的是，即使在量化之前，它也显着降低了特征的表现力。在本文中，我们表明上面的量化损失的定义太有限了，实际上对于保持高检索精度来说是不必要的。因此，我们提出一种以三元组度量的新的量化损失形式。三重量化损失的核心思想是学习量化后导致检索精度损失最小的判别性实值描述符。在两个广泛使用的不同规模的基准数据集CIFAR-10和In-shop上的大量实验表明，所提出的方法优于最先进的深度哈希方法。此外，我们证明了三重量化损失所得到的紧致二进制描述符在量化后会导致非常小的性能下降。

##### URL
[https://arxiv.org/abs/1710.11445](https://arxiv.org/abs/1710.11445)

##### PDF
[https://arxiv.org/pdf/1710.11445](https://arxiv.org/pdf/1710.11445)

