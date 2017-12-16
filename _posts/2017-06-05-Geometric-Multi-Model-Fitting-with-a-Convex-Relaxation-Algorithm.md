---
layout: post
title: "Geometric Multi-Model Fitting with a Convex Relaxation Algorithm"
date: 2017-06-05 22:49:59
categories: arXiv_CV
tags: arXiv_CV Classification
author: Paul Amayo, Pedro Pinies, Lina M. Paz, Paul Newman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method to fit and segment multi-structural data via convex relaxation. Unlike greedy methods --which maximise the number of inliers-- this approach efficiently searches for a soft assignment of points to models by minimising the energy of the overall classification. Our approach is similar to state-of-the-art energy minimisation techniques which use a global energy. However, we deal with the scaling factor (as the number of models increases) of the original combinatorial problem by relaxing the solution. This relaxation brings two advantages: first, by operating in the continuous domain we can parallelize the calculations. Second, it allows for the use of different metrics which results in a more general formulation. We demonstrate the versatility of our technique on two different problems of estimating structure from images: plane extraction from RGB-D data and homography estimation from pairs of images. In both cases, we report accurate results on publicly available datasets, in most of the cases outperforming the state-of-the-art.

##### Abstract (translated by Google)
我们提出了一种通过凸松弛拟合和分割多结构数据的新方法。与贪婪方法不同，它使内点数量最大化 - 这种方法通过最小化整体分类的能量来高效地搜索模型点的软分配。我们的方法类似于使用全球能源的最先进的能量最小化技术。然而，我们通过放宽解决方案来处理原始组合问题的比例因子（随着模型数量的增加）。这种放松带来两个好处：首先，通过在连续的领域中操作，我们可以并行计算。其次，它允许使用不同的度量标准，从而形成更一般的公式。我们展示了我们的技术的多功能性在两个不同的问题，从图像估计结构：平面提取RGB-D数据和单对估计从图像对。在这两种情况下，我们在公开可用的数据集上报告准确的结果，大多数情况下性能都超过了最新的数据。

##### URL
[https://arxiv.org/abs/1706.01553](https://arxiv.org/abs/1706.01553)

##### PDF
[https://arxiv.org/pdf/1706.01553](https://arxiv.org/pdf/1706.01553)

