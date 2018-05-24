---
layout: post
title: "Cramer-Wold AutoEncoder"
date: 2018-05-23 15:48:31
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Jacek Tabor, Szymon Knop, Przemys&#x142;aw Spurek, Igor Podolak, Marcin Mazur, Stanis&#x142;aw Jastrz&#x119;bski
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new generative model, Cramer-Wold Autoencoder (CWAE). Following WAE, we directly encourage normality of the latent space. Our paper uses also the recent idea from Sliced WAE (SWAE) model, which uses one-dimensional projections as a method of verifying closeness of two distributions. 
 The crucial new ingredient is the introduction of a new (Cramer-Wold) metric in the space of densities, which replaces the Wasserstein metric used in SWAE. We show that the Cramer-Wold metric between Gaussian mixtures is given by a simple analytic formula, which results in the removal of sampling necessary to estimate the cost function in WAE and SWAE models. 
 As a consequence, while drastically simplifying the optimization procedure, CWAE produces samples of a matching perceptual quality to other SOTA models.

##### Abstract (translated by Google)
我们提出了一个新的生成模型，即Cramer-Wold自动编码器（CWAE）。在WAE之后，我们直接鼓励潜在空间的正常性。我们的论文还使用了来自Sliced WAE（SWAE）模型的最近想法，该模型使用一维投影作为验证两个分布紧密度的方法。
 关键的新成分是在密度空间中引入新的（Cramer-Wold）度量，它取代了SWAE中使用的Wasserstein度量。我们证明高斯混合之间的Cramer-Wold度量是由一个简单的分析公式给出的，这导致了在WAE和SWAE模型中估计成本函数所必需的取样的去除。
 因此，CWAE在大幅简化优化程序的同时，为其他SOTA模型生成匹配感知质量的样本。

##### URL
[http://arxiv.org/abs/1805.09235](http://arxiv.org/abs/1805.09235)

##### PDF
[http://arxiv.org/pdf/1805.09235](http://arxiv.org/pdf/1805.09235)

