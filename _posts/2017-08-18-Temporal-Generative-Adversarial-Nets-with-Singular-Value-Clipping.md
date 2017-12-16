---
layout: post
title: "Temporal Generative Adversarial Nets with Singular Value Clipping"
date: 2017-08-18 02:32:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Masaki Saito, Eiichi Matsumoto, Shunta Saito
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a generative model, Temporal Generative Adversarial Nets (TGAN), which can learn a semantic representation of unlabeled videos, and is capable of generating videos. Unlike existing Generative Adversarial Nets (GAN)-based methods that generate videos with a single generator consisting of 3D deconvolutional layers, our model exploits two different types of generators: a temporal generator and an image generator. The temporal generator takes a single latent variable as input and outputs a set of latent variables, each of which corresponds to an image frame in a video. The image generator transforms a set of such latent variables into a video. To deal with instability in training of GAN with such advanced networks, we adopt a recently proposed model, Wasserstein GAN, and propose a novel method to train it stably in an end-to-end manner. The experimental results demonstrate the effectiveness of our methods.

##### Abstract (translated by Google)
在本文中，我们提出了一个生成模型，即时间生成对抗网络（TGAN），它可以学习未标记视频的语义表示，并且能够生成视频。不同于现有的基于生成敌对网络（GAN）的方法，它们使用由3D去卷积层组成的单个生成器来生成视频，我们的模型利用两种不同类型的生成器：时间生成器和图像生成器。时间发生器将单个潜变量作为输入，并输出一组潜变量，每个潜变量对应于视频中的图像帧。图像生成器将一组这样的潜在变量转换成视频。针对这种先进网络对GAN进行训练的不稳定性，采用最近提出的模型Wasserstein GAN，提出了一种端到端稳定训练的新方法。实验结果证明了我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1611.06624](https://arxiv.org/abs/1611.06624)

##### PDF
[https://arxiv.org/pdf/1611.06624](https://arxiv.org/pdf/1611.06624)

