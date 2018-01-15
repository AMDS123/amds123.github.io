---
layout: post
title: "Conditional Probability Models for Deep Image Compression"
date: 2018-01-12 18:29:05
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN
author: Fabian Mentzer, Eirikur Agustsson, Michael Tschannen, Radu Timofte, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Neural Networks trained as image auto-encoders have recently emerged as a promising direction for advancing the state of the art in image compression. The key challenge in learning such networks is twofold: to deal with quantization, and to control the trade-off between reconstruction error (distortion) and entropy (rate) of the latent image representation. In this paper, we focus on the latter challenge and propose a new technique to navigate the rate-distortion trade-off for an image compression auto-encoder. The main idea is to directly model the entropy of the latent representation by using a context model: a 3D-CNN which learns a conditional probability model of the latent distribution of the auto-encoder. During training, the auto-encoder makes use of the context model to estimate the entropy of its representation, and the context model is concurrently updated to learn the dependencies between the symbols in the latent representation. Our experiments show that this approach yields a state-of-the-art image compression system based on a simple convolutional auto-encoder.

##### Abstract (translated by Google)
作为图像自动编码器训练的深度神经网络最近已经成为推进图像压缩技术发展的一个有希望的方向。学习这样的网络的关键挑战是双重的：处理量化，并控制潜在表示的重构误差（失真）和熵（速率）之间的折衷。在本文中，我们关注后一个挑战，并提出了一种新的技术来导航图像压缩自动编码器的速率 - 失真权衡。其主要思想是通过使用上下文模型来直接对潜在表示的熵进行建模：3D-CNN，其学习自动编码器的潜在分布的条件概率模型。在训练期间，自动编码器利用上下文模型来估计其表示的熵，并且同时更新上下文模型以学习潜在表示中的符号之间的依赖关系。我们的实验表明，这种方法产生了一个基于简单的卷积自动编码器的最先进的图像压缩系统。

##### URL
[http://arxiv.org/abs/1801.04260](http://arxiv.org/abs/1801.04260)

##### PDF
[http://arxiv.org/pdf/1801.04260](http://arxiv.org/pdf/1801.04260)

