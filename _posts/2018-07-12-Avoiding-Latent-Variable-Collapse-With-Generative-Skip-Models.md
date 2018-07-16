---
layout: post
title: "Avoiding Latent Variable Collapse With Generative Skip Models"
date: 2018-07-12 23:37:27
categories: arXiv_CL
tags: arXiv_CL
author: Adji B. Dieng, Yoon Kim, Alexander M. Rush, David M. Blei
mathjax: true
---

* content
{:toc}

##### Abstract
Variational autoencoders (VAEs) learn distributions of high-dimensional data. They model data by introducing a deep latent-variable model and then maximizing a lower bound of the log marginal likelihood. While VAEs can capture complex distributions, they also suffer from an issue known as "latent variable collapse." Specifically, the lower bound involves an approximate posterior of the latent variables; this posterior "collapses" when it is set equal to the prior, i.e., when the posterior is independent of the data. While VAEs learn good generative models, latent variable collapse prevents them from learning useful representations. In this paper, we propose a new way to avoid latent variable collapse. We expand the model class to one that includes skip connections; these connections enforce strong links between the latent variables and the likelihood function. We study these generative skip models both theoretically and empirically. Theoretically, we prove that skip models increase the mutual information between the observations and the inferred latent variables. Empirically, on both images (MNIST and Omniglot) and text (Yahoo), we show that generative skip models lead to less collapse than existing VAE architectures.

##### Abstract (translated by Google)
变分自动编码器（VAE）学习高维数据的分布。他们通过引入深潜变量模型然后最大化对数边际可能性的下限来对数据建模。虽然VAE可以捕获复杂的分布，但它们也会遇到一个被称为“潜在变量崩溃”的问题。具体而言，下限涉及潜在变量的近似后验;当它被设置为等于先前时，即当后验独立于数据时，这个后“坍塌”。虽然VAE学习良好的生成模型，但潜变量崩溃阻止他们学习有用的表示。在本文中，我们提出了一种避免潜在变量崩溃的新方法。我们将模型类扩展为包含跳过连接的类;这些连接强制潜在变量和似然函数之间的强连接。我们从理论上和经验上研究这些生成跳过模型。从理论上讲，我们证明跳过模型增加了观测值与推断的潜在变量之间的互信息。根据经验，在图像（MNIST和Omniglot）和文本（Yahoo）上，我们表明生成跳过模型导致比现有VAE架构更少崩溃。

##### URL
[http://arxiv.org/abs/1807.04863](http://arxiv.org/abs/1807.04863)

##### PDF
[http://arxiv.org/pdf/1807.04863](http://arxiv.org/pdf/1807.04863)

