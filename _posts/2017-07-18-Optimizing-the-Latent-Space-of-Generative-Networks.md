---
layout: post
title: "Optimizing the Latent Space of Generative Networks"
date: 2017-07-18 17:58:34
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Optimization
author: Piotr Bojanowski, Armand Joulin, David Lopez-Paz, Arthur Szlam
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have been shown to be able to sample impressively realistic images. GAN training consists of a saddle point optimization problem that can be thought of as an adversarial game between a generator which produces the images, and a discriminator, which judges if the images are real. Both the generator and the discriminator are commonly parametrized as deep convolutional neural networks. The goal of this paper is to disentangle the contribution of the optimization procedure and the network parametrization to the success of GANs. To this end we introduce and study Generative Latent Optimization (GLO), a framework to train a generator without the need to learn a discriminator, thus avoiding challenging adversarial optimization problems. We show experimentally that GLO enjoys many of the desirable properties of GANs: learning from large data, synthesizing visually-appealing samples, interpolating meaningfully between samples, and performing linear arithmetic with noise vectors.

##### Abstract (translated by Google)
生成敌对网络（GAN）已被证明能够采样令人印象深刻的逼真图像。 GAN训练由一个鞍点优化问题组成，这个问题可以被看作是产生图像的发生器和鉴别图像是否真实的鉴别器之间的对抗性游戏。发生器和鉴别器通常被参数化为深度卷积神经网络。本文的目的是解决优化程序和网络参数化对GAN成功的贡献。为此，我们引入并研究了生成潜在优化（Generative Latent Optimization，GLO），这是一个不需要学习鉴别器就可以训练生成器的框架，从而避免了挑战性的对抗优化问题。我们通过实验表明，GLO享有许多GAN的理想特性：从大数据中学习，合成视觉吸引力的样本，在样本之间进行有意义的插值，以及用噪声向量执行线性运算。

##### URL
[https://arxiv.org/abs/1707.05776](https://arxiv.org/abs/1707.05776)

##### PDF
[https://arxiv.org/pdf/1707.05776](https://arxiv.org/pdf/1707.05776)

