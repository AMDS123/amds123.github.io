---
layout: post
title: "VAE with a VampPrior"
date: 2018-02-26 15:23:53
categories: arXiv_AI
tags: arXiv_AI Face CNN
author: Jakub M. Tomczak, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
Many different methods to train deep generative models have been introduced in the past. In this paper, we propose to extend the variational auto-encoder (VAE) framework with a new type of prior which we call "Variational Mixture of Posteriors" prior, or VampPrior for short. The VampPrior consists of a mixture distribution (e.g., a mixture of Gaussians) with components given by variational posteriors conditioned on learnable pseudo-inputs. We further extend this prior to a two layer hierarchical model and show that this architecture with a coupled prior and posterior, learns significantly better models. The model also avoids the usual local optima issues related to useless latent dimensions that plague VAEs. We provide empirical studies on six datasets, namely, static and binary MNIST, OMNIGLOT, Caltech 101 Silhouettes, Frey Faces and Histopathology patches, and show that applying the hierarchical VampPrior delivers state-of-the-art results on all datasets in the unsupervised permutation invariant setting and the best results or comparable to SOTA methods for the approach with convolutional networks.

##### Abstract (translated by Google)
过去引入了许多不同的培养深度生成模型的方法。在本文中，我们建议使用先前称为“变形混合物后处理”的新型变形自动编码器（VAE）框架，或简称为VampPrior。 VampPrior由混合分布（例如，高斯混合）组成，其分量由可变假设输入条件下的变分后验给出。我们在进一步扩展这个两层分层模型之前，展示了这个结合了先验和后验的架构，学习了更好的模型。该模型还避免了与无用的潜在维度相关的常见局部最优化问题，这些问题困扰着VAE。我们提供了六个数据集的实证研究，即静态和二元MNIST，OMNIGLOT，Caltech 101 Silhouettes，Frey Faces和组织病理学补丁，并表明应用分层VampPrior可在无监督置换的所有数据集上提供最新的结果不变的设置和最佳的结果，或者与SOTA方法相比，用于卷积网络的方法。

##### URL
[http://arxiv.org/abs/1705.07120](http://arxiv.org/abs/1705.07120)

##### PDF
[http://arxiv.org/pdf/1705.07120](http://arxiv.org/pdf/1705.07120)

