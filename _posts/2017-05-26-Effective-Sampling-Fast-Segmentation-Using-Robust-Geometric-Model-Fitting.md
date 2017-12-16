---
layout: post
title: "Effective Sampling: Fast Segmentation Using Robust Geometric Model Fitting"
date: 2017-05-26 05:39:07
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ruwan Tennakoon, Alireza Sadri, Reza Hoseinnezhad, Alireza Bab-Hadiashar
mathjax: true
---

* content
{:toc}

##### Abstract
Identifying the underlying models in a set of data points contaminated by noise and outliers, leads to a highly complex multi-model fitting problem. This problem can be posed as a clustering problem by the projection of higher order affinities between data points into a graph, which can then be clustered using spectral clustering. Calculating all possible higher order affinities is computationally expensive. Hence in most cases only a subset is used. In this paper, we propose an effective sampling method to obtain a highly accurate approximation of the full graph required to solve multi-structural model fitting problems in computer vision. The proposed method is based on the observation that the usefulness of a graph for segmentation improves as the distribution of hypotheses (used to build the graph) approaches the distribution of actual parameters for the given data. In this paper, we approximate this actual parameter distribution using a k-th order statistics based cost function and the samples are generated using a greedy algorithm coupled with a data sub-sampling strategy. The experimental analysis shows that the proposed method is both accurate and computationally efficient compared to the state-of-the-art robust multi-model fitting techniques. The code is publicly available from this https URL

##### Abstract (translated by Google)
识别由噪声和异常值污染的一组数据点中的基本模型导致高度复杂的多模型拟合问题。这个问题可以通过将数据点之间的高阶亲和度投影到一个图中，然后使用谱聚类进行聚类而形成聚类问题。计算所有可能的高阶亲和力在计算上是昂贵的。因此在大多数情况下只使用一个子集。在本文中，我们提出了一种有效的抽样方法，以获得计算机视觉中解决多结构模型拟合问题所需的全图的高精度近似。所提出的方法基于以下观察结果：随着假设的分布（用于构建图）接近给定数据的实际参数的分布，用于分割的图的有用性得到改善。在本文中，我们使用基于k阶的基于统计的成本函数近似这个实际参数分布，并且使用结合数据子采样策略的贪婪算法来生成样本。实验分析表明，与现有技术的稳健多模型拟合技术相比，所提出的方法既精确又有计算效率。该代码可从此https URL公开获得

##### URL
[https://arxiv.org/abs/1705.09437](https://arxiv.org/abs/1705.09437)

##### PDF
[https://arxiv.org/pdf/1705.09437](https://arxiv.org/pdf/1705.09437)

