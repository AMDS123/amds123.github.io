---
layout: post
title: "Coarse-to-fine Seam Estimation for Image Stitching"
date: 2018-05-24 09:49:06
categories: arXiv_CV
tags: arXiv_CV Relation
author: Tianli Liao, Jing Chen, Yifang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Seam-cutting and seam-driven techniques have been proven effective for handling imperfect image series in image stitching. Generally, seam-driven is to utilize seam-cutting to find a best seam from one or finite alignment hypotheses based on a predefined seam quality metric. However, the quality metrics in most methods are defined to measure the average performance of the pixels on the seam without considering the relevance and variance among them. This may cause that the seam with the minimal measure is not optimal (perception-inconsistent) in human perception. In this paper, we propose a novel coarse-to-fine seam estimation method which applies the evaluation in a different way. For pixels on the seam, we develop a patch-point evaluation algorithm concentrating more on the correlation and variation of them. The evaluations are then used to recalculate the difference map of the overlapping region and reestimate a stitching seam. This evaluation-reestimation procedure iterates until the current seam changes negligibly comparing with the previous seams. Experiments show that our proposed method can finally find a nearly perception-consistent seam after several iterations, which outperforms the conventional seam-cutting and other seam-driven methods.

##### Abstract (translated by Google)
缝合切割和接缝驱动技术已被证明可有效处理图像拼接中不完美的图像系列。一般来说，接缝驱动是利用切缝从一个或者有限的对齐假设中找到一个最好的接缝，这个假设是基于预定义的接缝质量度量。然而，大多数方法中的质量度量被定义为测量接缝上像素的平均性能，而不考虑它们之间的相关性和方差。这可能导致具有最小量度的接缝在人类感知中不是最佳的（感知不一致）。在本文中，我们提出了一种新颖的从粗到细的缝估计方法，以不同的方式应用评估。对于接缝上的像素，我们开发了一个补丁点评估算法，更多地关注它们的相关性和变化。然后使用评估重新计算重叠区域的差异图并重新拼接缝合线。这个评估重新估计过程会迭代，直到当前接缝与之前的接缝相比可以忽略不计。实验表明，我们提出的方法可以在几次迭代之后最终找到几乎感知一致的接缝，这比传统的切缝和其他接缝驱动的方法更胜一筹。

##### URL
[http://arxiv.org/abs/1805.09578](http://arxiv.org/abs/1805.09578)

##### PDF
[http://arxiv.org/pdf/1805.09578](http://arxiv.org/pdf/1805.09578)

