---
layout: post
title: "A Nonlinear Dimensionality Reduction Framework Using Smooth Geodesics"
date: 2018-07-13 17:38:33
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding
author: Kelum Gajamannage, Randy Paffenroth, Erik M. Bollt
mathjax: true
---

* content
{:toc}

##### Abstract
Existing dimensionality reduction methods are adept at revealing hidden underlying manifolds arising from high-dimensional data and thereby producing a low-dimensional representation. However, the smoothness of the manifolds produced by classic techniques over sparse and noisy data is not guaranteed. In fact, the embedding generated using such data may distort the geometry of the manifold and thereby produce an unfaithful embedding. Herein, we propose a framework for nonlinear dimensionality reduction that generates a manifold in terms of smooth geodesics that is designed to treat problems in which manifold measurements are either sparse or corrupted by noise. Our method generates a network structure for given high-dimensional data using a nearest neighbors search and then produces piecewise linear shortest paths that are defined as geodesics. Then, we fit points in each geodesic by a smoothing spline to emphasize the smoothness. The robustness of this approach for sparse and noisy datasets is demonstrated by the implementation of the method on synthetic and real-world datasets.

##### Abstract (translated by Google)
现有的降维方法擅长于揭示由高维数据产生的隐藏的底层流形，从而产生低维表示。然而，不保证经典技术产生的流形在稀疏和噪声数据上的平滑性。事实上，使用这种数据生成的嵌入可能会扭曲歧管的几何形状，从而产生不忠实的嵌入。在这里，我们提出了一个非线性降维的框架，它在平滑测地线方面产生一个流形，旨在处理歧管测量稀疏或被噪声破坏的问题。我们的方法使用最近邻搜索为给定的高维数据生成网络结构，然后生成被定义为测地线的分段线性最短路径。然后，我们通过平滑样条拟合每个测地线中的点以强调平滑度。通过在合成和真实世界数据集上实施该方法，证明了这种方法对稀疏和噪声数据集的稳健性。

##### URL
[http://arxiv.org/abs/1707.06757](http://arxiv.org/abs/1707.06757)

##### PDF
[http://arxiv.org/pdf/1707.06757](http://arxiv.org/pdf/1707.06757)

