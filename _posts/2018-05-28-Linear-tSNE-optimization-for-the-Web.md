---
layout: post
title: "Linear tSNE optimization for the Web"
date: 2018-05-28 08:49:46
categories: arXiv_AI
tags: arXiv_AI Embedding Optimization
author: Nicola Pezzotti, Alexander Mordvintsev, Thomas Hollt, Boudewijn P.F. Lelieveldt, Elmar Eisemann, Anna Vilanova
mathjax: true
---

* content
{:toc}

##### Abstract
The t-distributed Stochastic Neighbor Embedding (tSNE) algorithm has become in recent years one of the most used and insightful techniques for the exploratory data analysis of high-dimensional data. tSNE reveals clusters of high-dimensional data points at different scales while it requires only minimal tuning of its parameters. Despite these advantages, the computational complexity of the algorithm limits its application to relatively small datasets. To address this problem, several evolutions of tSNE have been developed in recent years, mainly focusing on the scalability of the similarity computations between data points. However, these contributions are insufficient to achieve interactive rates when visualizing the evolution of the tSNE embedding for large datasets. In this work, we present a novel approach to the minimization of the tSNE objective function that heavily relies on modern graphics hardware and has linear computational complexity. Our technique does not only beat the state of the art, but can even be executed on the client side in a browser. We propose to approximate the repulsion forces between data points using adaptive-resolution textures that are drawn at every iteration with WebGL. This approximation allows us to reformulate the tSNE minimization problem as a series of tensor operation that are computed with TensorFlow.js, a JavaScript library for scalable tensor computations.

##### Abstract (translated by Google)
t分布随机相邻嵌入（tSNE）算法近年来已成为高维数据探索性数据分析中使用最多，最有洞察力的技术之一。 tSNE揭示了不同尺度下高维数据点的聚类，而只需要对其参数进行微调。尽管有这些优点，算法的计算复杂度限制了其应用于相对较小的数据集。为了解决这个问题，最近几年发展了几种tSNE的发展，主要集中在数据点之间相似性计算的可扩展性。然而，当可视化大型数据集的tSNE嵌入演进时，这些贡献不足以实现交互式速率。在这项工作中，我们提出了一种新颖的方法来最大限度地减少tSNE目标函数，该函数严重依赖于现代图形硬件并具有线性计算复杂度。我们的技术不仅能够击败最先进的技术，甚至可以在浏览器中在客户端执行。我们建议使用WebGL在每次迭代中绘制的自适应分辨率纹理来近似数据点之间的排斥力。这个近似允许我们将tSNE最小化问题重新表达为一系列张量运算，这些运算是用TensorFlow.js（一个用于可伸缩张量计算的JavaScript库）计算出来的。

##### URL
[http://arxiv.org/abs/1805.10817](http://arxiv.org/abs/1805.10817)

##### PDF
[http://arxiv.org/pdf/1805.10817](http://arxiv.org/pdf/1805.10817)

