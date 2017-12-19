---
layout: post
title: "Aggregating Deep Convolutional Features for Image Retrieval"
date: 2015-10-26 14:35:26
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Image_Classification Classification
author: Artem Babenko, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
Several recent works have shown that image descriptors produced by deep convolutional neural networks provide state-of-the-art performance for image classification and retrieval problems. It has also been shown that the activations from the convolutional layers can be interpreted as local features describing particular image regions. These local features can be aggregated using aggregation approaches developed for local features (e.g. Fisher vectors), thus providing new powerful global descriptors. In this paper we investigate possible ways to aggregate local deep features to produce compact global descriptors for image retrieval. First, we show that deep features and traditional hand-engineered features have quite different distributions of pairwise similarities, hence existing aggregation methods have to be carefully re-evaluated. Such re-evaluation reveals that in contrast to shallow features, the simple aggregation method based on sum pooling provides arguably the best performance for deep convolutional features. This method is efficient, has few parameters, and bears little risk of overfitting when e.g. learning the PCA matrix. Overall, the new compact global descriptor improves the state-of-the-art on four common benchmarks considerably.

##### Abstract (translated by Google)
最近的几项研究表明，深度卷积神经网络产生的图像描述符为图像分类和检索问题提供了最先进的性能。也已经显示来自卷积层的激活可以被解释为描述特定图像区域的局部特征。这些局部特征可以使用针对局部特征（例如Fisher向量）开发的聚合方法进行聚合，从而提供新的强大的全局描述符。在本文中，我们调查了可能的方法来聚合局部深度特征以产生用于图像检索的紧凑全局描述符。首先，我们发现深度特征和传统的手工特征具有完全不同的成对相似性分布，因此现有的聚合方法必须仔细重新评估。这种重新评估表明，与浅层特征相比，基于和池的简单聚合方法可以说是深层卷积特征的最佳表现。这种方法效率高，参数少，在例如过度拟合时几乎没有风险。学习PCA矩阵。总的来说，新的紧凑的全局描述符大大改善了四个通用基准的最新技术水平。

##### URL
[https://arxiv.org/abs/1510.07493](https://arxiv.org/abs/1510.07493)

##### PDF
[https://arxiv.org/pdf/1510.07493](https://arxiv.org/pdf/1510.07493)

