---
layout: post
title: "A GPU-Oriented Algorithm Design for Secant-Based Dimensionality Reduction"
date: 2018-07-10 00:02:16
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Henry Kvinge, Elin Farnell, Michael Kirby, Chris Peterson
mathjax: true
---

* content
{:toc}

##### Abstract
Dimensionality-reduction techniques are a fundamental tool for extracting useful information from high-dimensional data sets. Because secant sets encode manifold geometry, they are a useful tool for designing meaningful data-reduction algorithms. In one such approach, the goal is to construct a projection that maximally avoids secant directions and hence ensures that distinct data points are not mapped too close together in the reduced space. This type of algorithm is based on a mathematical framework inspired by the constructive proof of Whitney's embedding theorem from differential topology. Computing all (unit) secants for a set of points is by nature computationally expensive, thus opening the door for exploitation of GPU architecture for achieving fast versions of these algorithms. We present a polynomial-time data-reduction algorithm that produces a meaningful low-dimensional representation of a data set by iteratively constructing improved projections within the framework described above. Key to our algorithm design and implementation is the use of GPUs which, among other things, minimizes the computational time required for the calculation of all secant lines. One goal of this report is to share ideas with GPU experts and to discuss a class of mathematical algorithms that may be of interest to the broader GPU community.

##### Abstract (translated by Google)
降维技术是从高维数据集中提取有用信息的基本工具。因为割线集编码流形几何，它们是设计有意义的数据缩减算法的有用工具。在一种这样的方法中，目标是构建最大程度地避免正割方向的投影，并因此确保不同的数据点在缩小的空间中不会太靠近地映射。这种类型的算法基于一个数学框架，该框架的灵感来自于来自差分拓扑的Whitney嵌入定理的建设性证明。计算一组点的所有（单位）割线本质上是计算上昂贵的，因此为利用GPU架构打开了大门，以实现这些算法的快速版本。我们提出了一种多项式时间数据减少算法，该算法通过在上述框架内迭代地构造改进的投影来产生数据集的有意义的低维表示。我们的算法设计和实现的关键是使用GPU，其中，最小化计算所有割线所需的计算时间。本报告的一个目标是与GPU专家分享想法，并讨论一类可能对更广泛的GPU社区感兴趣的数学算法。

##### URL
[http://arxiv.org/abs/1807.03425](http://arxiv.org/abs/1807.03425)

##### PDF
[http://arxiv.org/pdf/1807.03425](http://arxiv.org/pdf/1807.03425)

