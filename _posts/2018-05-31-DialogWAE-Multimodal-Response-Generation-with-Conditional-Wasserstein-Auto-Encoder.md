---
layout: post
title: "DialogWAE: Multimodal Response Generation with Conditional Wasserstein Auto-Encoder"
date: 2018-05-31 07:25:04
categories: arXiv_AI
tags: arXiv_AI GAN
author: Xiaodong Gu, Kyunghyun Cho, Jungwoo Ha, Sunghun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Variational autoencoders (VAEs) have shown a promise in data-driven conversation modeling. However, most VAE conversation models match the approximate posterior distribution over the latent variables to a simple prior such as standard normal distribution, thereby restricting the generated responses to a relatively simple (e.g., single-modal) scope. In this paper, we propose DialogWAE, a conditional Wasserstein autoencoder (WAE) specially designed for dialogue modeling. Unlike VAEs that impose a simple distribution over the latent variables, DialogWAE models the distribution of data by training a GAN within the latent variable space. Specifically, our model samples from the prior and posterior distributions over the latent variables by transforming context-dependent random noise using neural networks and minimizes the Wasserstein distance between the two distributions. We further develop a Gaussian mixture prior network to enrich the latent space. Experiments on two widely-used datasets show that DialogWAE outperforms the state-of-the-art approaches in generating more coherent, informative and diverse responses.

##### Abstract (translated by Google)
变分自动编码器（VAEs）已经在数据驱动的对话建模中显示出承诺。然而，大多数VAE对话模型将潜在变量的近似后验分布与标准正态分布等简单事先匹配，从而将生成的响应限制在相对简单的（例如单一模式）范围内。在本文中，我们提出了专门为对话建模设计的DialogWAE，一种有条件的Wasserstein自动编码器（WAE）。与对潜在变量施加简单分布的VAE不同，DialogWAE通过在潜在变量空间内训练GAN来对数据分布进行建模。具体而言，我们的模型通过使用神经网络来变换与上下文相关的随机噪声，从潜在变量的先验和后验分布中采样并最小化两个分布之间的Wasserstein距离。我们进一步开发高斯混合先验网络来丰富潜在空间。对两个广泛使用的数据集进行的实验表明，DialogWAE在生成更连贯，信息丰富和多样化的响应方面优于最先进的方法。

##### URL
[http://arxiv.org/abs/1805.12352](http://arxiv.org/abs/1805.12352)

##### PDF
[http://arxiv.org/pdf/1805.12352](http://arxiv.org/pdf/1805.12352)

