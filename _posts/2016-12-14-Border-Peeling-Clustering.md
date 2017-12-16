---
layout: post
title: "Border-Peeling Clustering"
date: 2016-12-14 22:22:41
categories: arXiv_CV
tags: arXiv_CV CNN
author: Nadav Bar, Hadar Averbuch-Elor, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel non-parametric clustering technique, which is based on an iterative algorithm that peels off layers of points around the clusters. Our technique is based on the notion that each latent cluster is comprised of layers that surround its core, where the external layers, or border points, implicitly separate the clusters. Analyzing the K-nearest neighbors of the points makes it possible to identify the border points and associate them with points of inner layers. Our clustering algorithm iteratively identifies border points, peels them, and separates the latent clusters. We show that the peeling process adapts to the local density and successfully separates adjacent clusters. A notable quality of the Border-Peeling algorithm is that it does not require any parameter tuning in order to outperform state-of-the-art finely-tuned non-parametric clustering methods, including Mean-Shift and DBSCAN. We further assess our technique on high-dimensional datasets that vary in size and characteristics. In particular, we analyze the space of deep features that were trained by a convolutional neural network.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的非参数聚类技术，它是基于一个迭代算法，剥离集群周围的点层。我们的技术是基于这样的概念，即每个潜在簇由围绕其核心的层组成，其中外部层或边界点隐含地分离簇。分析点的K近邻可以确定边界点并将它们与内层的点相关联。我们的聚类算法迭代地识别边界点，剥离它们，并分离潜在的聚类。我们表明，剥离过程适应当地的密度，并成功地分隔相邻的集群。 Border-Peeling算法的一个显着特点是不需要任何参数调整就可以胜过最先进的精细调整的非参数聚类方法，包括Mean-Shift和DBSCAN。我们进一步评估我们的技术在尺寸和特征各不相同的高维数据集上。具体而言，我们分析了卷积神经网络训练的深度特征的空间。

##### URL
[https://arxiv.org/abs/1612.04869](https://arxiv.org/abs/1612.04869)

##### PDF
[https://arxiv.org/pdf/1612.04869](https://arxiv.org/pdf/1612.04869)

