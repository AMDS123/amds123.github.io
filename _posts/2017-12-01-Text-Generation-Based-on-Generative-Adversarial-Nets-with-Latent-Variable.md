---
layout: post
title: "Text Generation Based on Generative Adversarial Nets with Latent Variable"
date: 2017-12-01 03:14:51
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN CNN
author: Heng Wang, Zengchang Qin, Tao Wan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a model using generative adversarial net (GAN) to generate realistic text. Instead of using standard GAN, we combine variational autoencoder (VAE) with generative adversarial net. The use of high-level latent random variables is helpful to learn the data distribution and solve the problem that generative adversarial net always emits the similar data. We propose the VGAN model where the generative model is composed of recurrent neural network and VAE. The discriminative model is a convolutional neural network. We train the model via policy gradient. We apply the proposed model to the task of text generation and compare it to other recent neural network based models, such as recurrent neural network language model and SeqGAN. We evaluate the performance of the model by calculating negative log-likelihood and the BLEU score. We conduct experiments on three benchmark datasets, and results show that our model outperforms other previous models.

##### Abstract (translated by Google)
在本文中，我们提出了一个使用生成对抗网（GAN）生成逼真文本的模型。我们没有使用标准的GAN，而是将变分自动编码器（VAE）和生成对抗网络结合起来。高级潜在随机变量的使用有助于学习数据分布，解决生成对抗网络总是发出类似数据的问题。我们提出了生成模型由递归神经网络和VAE组成的VGAN模型。判别模型是一个卷积神经网络。我们通过政策梯度来训练模型。将所提出的模型应用于文本生成任务，并将其与其他最新的神经网络模型（如递归神经网络语言模型和SeqGAN）进行比较。我们通过计算负对数似然和BLEU得分来评估模型的性能。我们对三个基准数据集进行了实验，结果表明，我们的模型胜过了以前的其他模型。

##### URL
[https://arxiv.org/abs/1712.00170](https://arxiv.org/abs/1712.00170)

