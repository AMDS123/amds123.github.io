---
layout: post
title: "Training VAEs Under Structured Residuals"
date: 2018-06-15 19:00:03
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Garoe Dorta, Sara Vicente, Lourdes Agapito, Neill D.F. Campbell, Ivor Simpson
mathjax: true
---

* content
{:toc}

##### Abstract
Variational auto-encoders (VAEs) are a popular and powerful deep generative model. Previous works on VAEs have assumed a factorized likelihood model, whereby the output uncertainty of each pixel is assumed to be independent. This approximation is clearly limited as demonstrated by observing a residual image from a VAE reconstruction, which often possess a high level of structure. This paper demonstrates a novel scheme to incorporate a structured Gaussian likelihood prediction network within the VAE that allows the residual correlations to be modeled. Our novel architecture, with minimal increase in complexity, incorporates the covariance matrix prediction within the VAE. We also propose a new mechanism for allowing structured uncertainty on color images. Furthermore, we provide a scheme for effectively training this model, and include some suggestions for improving performance in terms of efficiency or modeling longer range correlations.

##### Abstract (translated by Google)
变分自动编码器（VAEs）是一种流行且强大的深度生成模型。以前关于VAE的研究假设了一个分解似然模型，其中每个像素的输出不确定性被假定为独立的。通过观察通常具有高水平结构的VAE重建的残余图像来证明这种近似是明显受限的。本文演示了一种新的方案，在VAE内部结合了一个结构化的高斯似然预测网络，可以对残差相关性进行建模。我们的新型架构，复杂度最小化增加，将协方差矩阵预测纳入VAE。我们还提出了一种允许彩色图像上的结构不确定性的新机制。此外，我们提供了一个有效培训该模型的方案，并提供了一些关于提高效率或建立较长距离相关性的建议。

##### URL
[http://arxiv.org/abs/1804.01050](http://arxiv.org/abs/1804.01050)

##### PDF
[http://arxiv.org/pdf/1804.01050](http://arxiv.org/pdf/1804.01050)

