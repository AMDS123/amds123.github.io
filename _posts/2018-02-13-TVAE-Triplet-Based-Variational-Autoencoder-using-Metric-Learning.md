---
layout: post
title: "TVAE: Triplet-Based Variational Autoencoder using Metric Learning"
date: 2018-02-13 00:05:19
categories: arXiv_AI
tags: arXiv_AI Salient Embedding Represenation_Learning Inference
author: Haque Ishfaq, Assaf Hoogi, Daniel Rubin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep metric learning has been demonstrated to be highly effective in learning semantic representation and encoding information that can be used to measure data similarity, by relying on the embedding learned from metric learning. At the same time, variational autoencoder (VAE) has widely been used to approximate inference and proved to have a good performance for directed probabilistic models. However, for traditional VAE, the data label or feature information are intractable. Similarly, traditional representation learning approaches fail to represent many salient aspects of the data. In this project, we propose a novel integrated framework to learn latent embedding in VAE by incorporating deep metric learning. The features are learned by optimizing a triplet loss on the mean vectors of VAE in conjunction with standard evidence lower bound (ELBO) of VAE. This approach, which we call Triplet based Variational Autoencoder (TVAE), allows us to capture more fine-grained information in the latent embedding. Our model is tested on MNIST data set and achieves a high triplet accuracy of 95.60% while the traditional VAE (Kingma &amp; Welling, 2013) achieves triplet accuracy of 75.08%.

##### Abstract (translated by Google)
通过依靠从度量学习中学习的嵌入，深度量度学习在学习可用于度量数据相似度的语义表示和编码信息方面已被证明是非常有效的。同时，变分自动编码器（VAE）已被广泛用于近似推理，并被证明对定向概率模型具有良好的性能。但是，对于传统的VAE，数据标签或特征信息是棘手的。同样，传统的表示学习方法也不能代表数据的许多显着方面。在这个项目中，我们提出了一个新的集成框架，通过结合深度度量学习来学习VAE中的潜在嵌入。通过结合VAE的标准证据下限（ELBO）优化VAE的平均向量的三重损失来学习这些特征。这种我们称之为基于Triplet的变分自动编码器（TVAE）的方法允许我们在潜在嵌入中捕获更多细粒度的信息。我们的模型在MNIST数据集上进行测试，达到95.60％的高三重精度，而传统VAE（Kingma＆amp; Welling，2013）达到75.08％的三重精度。

##### URL
[http://arxiv.org/abs/1802.04403](http://arxiv.org/abs/1802.04403)

##### PDF
[http://arxiv.org/pdf/1802.04403](http://arxiv.org/pdf/1802.04403)

