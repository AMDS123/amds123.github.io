---
layout: post
title: "Integrating K-means with Quadratic Programming Feature Selection"
date: 2015-08-11 18:06:36
categories: arXiv_CV
tags: arXiv_CV
author: Yamuna Prasad, K. K. Biswas
mathjax: true
---

* content
{:toc}

##### Abstract
Several data mining problems are characterized by data in high dimensions. One of the popular ways to reduce the dimensionality of the data is to perform feature selection, i.e, select a subset of relevant and non-redundant features. Recently, Quadratic Programming Feature Selection (QPFS) has been proposed which formulates the feature selection problem as a quadratic program. It has been shown to outperform many of the existing feature selection methods for a variety of applications. Though, better than many existing approaches, the running time complexity of QPFS is cubic in the number of features, which can be quite computationally expensive even for moderately sized datasets. In this paper we propose a novel method for feature selection by integrating k-means clustering with QPFS. The basic variant of our approach runs k-means to bring down the number of features which need to be passed on to QPFS. We then enhance this idea, wherein we gradually refine the feature space from a very coarse clustering to a fine-grained one, by interleaving steps of QPFS with k-means clustering. Every step of QPFS helps in identifying the clusters of irrelevant features (which can then be thrown away), whereas every step of k-means further refines the clusters which are potentially relevant. We show that our iterative refinement of clusters is guaranteed to converge. We provide bounds on the number of distance computations involved in the k-means algorithm. Further, each QPFS run is now cubic in number of clusters, which can be much smaller than actual number of features. Experiments on eight publicly available datasets show that our approach gives significant computational gains (both in time and memory), over standard QPFS as well as other state of the art feature selection methods, even while improving the overall accuracy.

##### Abstract (translated by Google)
几个数据挖掘问题的特点是高维数据。减少数据维度的流行方法之一是执行特征选择，即选择相关和非冗余特征的子集。最近，提出了二次规划特征选择（QPFS），其将特征选择问题表示为二次程序。已经显示其在许多应用中胜过了许多现有的特征选择方法。虽然QPFS的运行时间复杂度比许多现有的方法要好，但是对于中等大小的数据集来说，QPFS的运行时间复杂度在特征数量上是立方的，这在计算上可能相当昂贵。在本文中，我们提出了一种通过集成k-means聚类和QPFS来进行特征选择的新方法。我们的方法的基本变体运行k-means来减少需要传递给QPFS的特征的数量。然后，我们提出这个想法，其中我们逐渐将特征空间从非常粗糙的聚类细化到细粒度的特征空间，通过QPFS与k均值聚类的交错步骤。 QPFS的每一步都有助于识别不相关特征的簇（然后可以被丢弃），而k-均值的每一步都会进一步细化可能相关的簇。我们表明，我们迭代的集群细化是保证收敛。我们提供k-means算法中涉及的距离计算的数量的界限。此外，每个QPFS运行现在是立方体的数量的聚类，可以远远小于实际数量的功能。在八个公开可用的数据集上的实验表明，我们的方法在标准QPFS以及其他现有技术特征选择方法中提供了显着的计算增益（包括时间和内存），即使在提高总体准确性的同时。

##### URL
[https://arxiv.org/abs/1505.01728](https://arxiv.org/abs/1505.01728)

##### PDF
[https://arxiv.org/pdf/1505.01728](https://arxiv.org/pdf/1505.01728)

