---
layout: post
title: "DialogWAE: Multimodal Response Generation with Conditional Wasserstein Auto-Encoder"
date: 2019-02-26 02:32:44
categories: arXiv_AI
tags: arXiv_AI GAN
author: Xiaodong Gu, Kyunghyun Cho, Jung-Woo Ha, Sunghun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Variational autoencoders~(VAEs) have shown a promise in data-driven conversation modeling. However, most VAE conversation models match the approximate posterior distribution over the latent variables to a simple prior such as standard normal distribution, thereby restricting the generated responses to a relatively simple (e.g., unimodal) scope. In this paper, we propose DialogWAE, a conditional Wasserstein autoencoder~(WAE) specially designed for dialogue modeling. Unlike VAEs that impose a simple distribution over the latent variables, DialogWAE models the distribution of data by training a GAN within the latent variable space. Specifically, our model samples from the prior and posterior distributions over the latent variables by transforming context-dependent random noise using neural networks and minimizes the Wasserstein distance between the two distributions. We further develop a Gaussian mixture prior network to enrich the latent space. Experiments on two popular datasets show that DialogWAE outperforms the state-of-the-art approaches in generating more coherent, informative and diverse responses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.12352](http://arxiv.org/abs/1805.12352)

##### PDF
[http://arxiv.org/pdf/1805.12352](http://arxiv.org/pdf/1805.12352)

