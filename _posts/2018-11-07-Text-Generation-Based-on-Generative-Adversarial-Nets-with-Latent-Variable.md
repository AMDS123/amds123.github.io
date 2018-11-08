---
layout: post
title: "Text Generation Based on Generative Adversarial Nets with Latent Variable"
date: 2018-11-07 12:27:23
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Text_Generation CNN Language_Model
author: Heng Wang, Zengchang Qin, Tao Wan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a model using generative adversarial net (GAN) to generate realistic text. Instead of using standard GAN, we combine variational autoencoder (VAE) with generative adversarial net. The use of high-level latent random variables is helpful to learn the data distribution and solve the problem that generative adversarial net always emits the similar data. We propose the VGAN model where the generative model is composed of recurrent neural network and VAE. The discriminative model is a convolutional neural network. We train the model via policy gradient. We apply the proposed model to the task of text generation and compare it to other recent neural network based models, such as recurrent neural network language model and SeqGAN. We evaluate the performance of the model by calculating negative log-likelihood and the BLEU score. We conduct experiments on three benchmark datasets, and results show that our model outperforms other previous models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.00170](http://arxiv.org/abs/1712.00170)

##### PDF
[http://arxiv.org/pdf/1712.00170](http://arxiv.org/pdf/1712.00170)

