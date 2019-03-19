---
layout: post
title: "Topic-Guided Variational Autoencoders for Text Generation"
date: 2019-03-17 17:42:29
categories: arXiv_CL
tags: arXiv_CL Text_Generation Inference
author: Wenlin Wang, Zhe Gan, Hongteng Xu, Ruiyi Zhang, Guoyin Wang, Dinghan Shen, Changyou Chen, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a topic-guided variational autoencoder (TGVAE) model for text generation. Distinct from existing variational autoencoder (VAE) based approaches, which assume a simple Gaussian prior for the latent code, our model specifies the prior as a Gaussian mixture model (GMM) parametrized by a neural topic module. Each mixture component corresponds to a latent topic, which provides guidance to generate sentences under the topic. The neural topic module and the VAE-based neural sequence module in our model are learned jointly. In particular, a sequence of invertible Householder transformations is applied to endow the approximate posterior of the latent code with high flexibility during model inference. Experimental results show that our TGVAE outperforms alternative approaches on both unconditional and conditional text generation, which can generate semantically-meaningful sentences with various topics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07137](http://arxiv.org/abs/1903.07137)

##### PDF
[http://arxiv.org/pdf/1903.07137](http://arxiv.org/pdf/1903.07137)

