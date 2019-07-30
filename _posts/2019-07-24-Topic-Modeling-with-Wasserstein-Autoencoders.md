---
layout: post
title: "Topic Modeling with Wasserstein Autoencoders"
date: 2019-07-24 14:08:23
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Feng Nan, Ran Ding, Ramesh Nallapati, Bing Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel neural topic model in the Wasserstein autoencoders (WAE) framework. Unlike existing variational autoencoder based models, we directly enforce Dirichlet prior on the latent document-topic vectors. We exploit the structure of the latent space and apply a suitable kernel in minimizing the Maximum Mean Discrepancy (MMD) to perform distribution matching. We discover that MMD performs much better than the Generative Adversarial Network (GAN) in matching high dimensional Dirichlet distribution. We further discover that incorporating randomness in the encoder output during training leads to significantly more coherent topics. To measure the diversity of the produced topics, we propose a simple topic uniqueness metric. Together with the widely used coherence measure NPMI, we offer a more wholistic evaluation of topic quality. Experiments on several real datasets show that our model produces significantly better topics than existing topic models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12374](http://arxiv.org/abs/1907.12374)

##### PDF
[http://arxiv.org/pdf/1907.12374](http://arxiv.org/pdf/1907.12374)

