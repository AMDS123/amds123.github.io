---
layout: post
title: "Fast and Efficient Depth Map Estimation from Light Fields"
date: 2018-05-01 10:20:35
categories: arXiv_CV
tags: arXiv_CV Semi_Global
author: Yuriy Anisimov, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
The paper presents an algorithm for depth map estimation from the light field images in relatively small amount of time, using only single thread on CPU. The proposed method improves existing principle of line fitting in 4-dimensional light field space. Line fitting is based on color values comparison using kernel density estimation. Our method utilizes result of Semi-Global Matching (SGM) with Census transform-based matching cost as a border initialization for line fitting. It provides a significant reduction of computations needed to find the best depth match. With the suggested evaluation metric we show that proposed method is applicable for efficient depth map estimation while preserving low computational time compared to others.

##### Abstract (translated by Google)
本文提出了一种在相对较少的时间内从光场图像进行深度图估计的算法，仅使用CPU上的单个线程。该方法改进了现有的四维光场空间中线拟合的原理。线拟合基于使用核密度估计的颜色值比较。我们的方法利用基于人口普查变换的匹配成本的半全局匹配（SGM）结果作为线拟合的边界初始化。它提供了显着减少计算所需的最佳深度匹配。通过建议的评估度量，我们证明了所提出的方法适用于有效的深度图估计，同时保持较低的计算时间。

##### URL
[https://arxiv.org/abs/1805.00264](https://arxiv.org/abs/1805.00264)

##### PDF
[https://arxiv.org/pdf/1805.00264](https://arxiv.org/pdf/1805.00264)

