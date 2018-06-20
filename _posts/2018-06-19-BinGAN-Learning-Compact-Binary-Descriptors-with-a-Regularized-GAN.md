---
layout: post
title: "BinGAN: Learning Compact Binary Descriptors with a Regularized GAN"
date: 2018-06-19 06:23:55
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Relation
author: Maciej Zieba, Piotr Semberecki, Tarek El-Gaaly, Tomasz Trzcinski
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel regularization method for Generative Adversarial Networks, which allows the model to learn discriminative yet compact binary representations of image patches (image descriptors). We employ the dimensionality reduction that takes place in the intermediate layers of the discriminator network and train binarized low-dimensional representation of the penultimate layer to mimic the distribution of the higher-dimensional preceding layers. To achieve this, we introduce two loss terms that aim at: (i) reducing the correlation between the dimensions of the binarized low-dimensional representation of the penultimate layer i. e. maximizing joint entropy) and (ii) propagating the relations between the dimensions in the high-dimensional space to the low-dimensional space. We evaluate the resulting binary image descriptors on two challenging applications, image matching and retrieval, and achieve state-of-the-art results.

##### Abstract (translated by Google)
在本文中，我们提出了一种用于生成敌对网络的新型正则化方法，该方法允许模型学习图像块（图像描述符）的有区别但紧凑的二进制表示。我们采用在鉴别器网络的中间层中发生的降维，并且训练倒数第二层的二进制低维表示以模拟较高维的在前层的分布。为了实现这一点，我们引入两个损失项，旨在：（i）减少倒数第二层i的二值化低维表示的维度之间的相关性。即最大化联合熵）和（ii）将高维空间中的维度之间的关系传播到低维空间。我们评估在两个具有挑战性的应用程序（图像匹配和检索）上产生的二进制图像描述符，并获得最新的结果。

##### URL
[http://arxiv.org/abs/1806.06778](http://arxiv.org/abs/1806.06778)

##### PDF
[http://arxiv.org/pdf/1806.06778](http://arxiv.org/pdf/1806.06778)

