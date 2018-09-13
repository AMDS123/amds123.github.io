---
layout: post
title: "Hyperprior Induced Unsupervised Disentanglement of Latent Representations"
date: 2018-09-12 14:53:19
categories: arXiv_AI
tags: arXiv_AI Face Relation
author: Abdul Fatir Ansari, Harold Soh
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of unsupervised disentanglement of latent representations learnt via deep generative models. In contrast to current approaches that operate on the evidence lower bound (ELBO), we argue that statistical independence in the latent space of VAEs can be enforced in a principled hierarchical Bayesian manner. To this effect, we augment the standard VAE with an inverse-Wishart (IW) prior on the covariance matrix of the latent code. By tuning the IW parameters, we are able to encourage (or discourage) independence in the learnt latent dimensions. Extensive experimental results on a range of datasets (2DShapes, 3DChairs, 3DFaces and CelebA) show our approach to outperform the $\beta$-VAE and is competitive with the state-of-the-art FactorVAE. Our approach achieves significantly better disentanglement and reconstruction on a new dataset (CorrelatedEllipses) which introduces correlations between the factors of variation.

##### Abstract (translated by Google)
我们解决了通过深度生成模型学习的潜在表征的无监督解开的问题。与目前采用证据下限（ELBO）的方法相反，我们认为VAE潜在空间中的统计独立性可以以原则性分层贝叶斯方式实施。为此，我们在潜在代码的协方差矩阵上使用逆Wishart（IW）先验扩充标准VAE。通过调整IW参数，我们能够鼓励（或阻止）在学习的潜在维度中的独立性。在一系列数据集（2DShapes，3DChairs，3DFaces和CelebA）上的广泛实验结果表明，我们的方法优于$ \ beta $ -VAE，并且与最先进的FactorVAE竞争。我们的方法在新数据集（CorrelatedEllipses）上实现了明显更好的解缠结和重建，这引入了变异因子之间的相关性。

##### URL
[http://arxiv.org/abs/1809.04497](http://arxiv.org/abs/1809.04497)

##### PDF
[http://arxiv.org/pdf/1809.04497](http://arxiv.org/pdf/1809.04497)

