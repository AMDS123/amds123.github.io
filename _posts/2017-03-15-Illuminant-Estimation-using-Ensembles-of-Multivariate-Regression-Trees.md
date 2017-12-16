---
layout: post
title: "Illuminant Estimation using Ensembles of Multivariate Regression Trees"
date: 2017-03-15 18:59:46
categories: arXiv_CV
tags: arXiv_CV
author: Peter van Beek, R. Wayne Oldford
mathjax: true
---

* content
{:toc}

##### Abstract
White balancing is a fundamental step in the image processing pipeline. The process involves estimating the chromaticity of the illuminant or light source and using the estimate to correct the image to remove any color cast. Given the importance of the problem, there has been much previous work on illuminant estimation. Recently, an approach based on ensembles of univariate regression trees that are fit using the squared-error loss function has been proposed and shown to give excellent performance. In this paper, we show that a simpler and more accurate ensemble model can be learned by (i) using multivariate regression trees to take into account that the chromaticity components of the illuminant are correlated and constrained, and (ii) fitting each tree by directly minimizing a loss function of interest---such as recovery angular error or reproduction angular error---rather than indirectly using the squared-error loss function as a surrogate. We show empirically that overall our method leads to improved performance on diverse image sets.

##### Abstract (translated by Google)
白平衡是图像处理流水线中的一个基本步骤。该过程涉及估计光源或光源的色度，并使用估计来校正图像以消除任何偏色。鉴于这个问题的重要性，以前在光源估计方面做了很多工作。近来，已经提出了一种基于使用平方误差损失函数拟合的单变量回归树的合奏方法，并表现出优异的性能。在本文中，我们表明，一个更简单和更准确的集成模型可以通过（i）使用多元回归树来考虑光源的色度分量相关和约束，和（ii）通过直接拟合每棵树使感兴趣的损失函数（例如恢复角度误差或再现角度误差）最小化，而不是间接地使用平方误差损失函数作为替代。我们经验地显示，我们的方法总体上导致不同图像集上的性能提高。

##### URL
[https://arxiv.org/abs/1703.05354](https://arxiv.org/abs/1703.05354)

##### PDF
[https://arxiv.org/pdf/1703.05354](https://arxiv.org/pdf/1703.05354)

