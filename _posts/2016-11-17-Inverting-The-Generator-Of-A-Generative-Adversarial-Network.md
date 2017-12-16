---
layout: post
title: "Inverting The Generator Of A Generative Adversarial Network"
date: 2016-11-17 11:55:16
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Adversarial GAN Image_Classification Classification
author: Antonia Creswell, Anil Anthony Bharath
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) learn to synthesise new samples from a high-dimensional distribution by passing samples drawn from a latent space through a generative network. When the high-dimensional distribution describes images of a particular data set, the network should learn to generate visually similar image samples for latent variables that are close to each other in the latent space. For tasks such as image retrieval and image classification, it may be useful to exploit the arrangement of the latent space by projecting images into it, and using this as a representation for discriminative tasks. GANs often consist of multiple layers of non-linear computations, making them very difficult to invert. This paper introduces techniques for projecting image samples into the latent space using any pre-trained GAN, provided that the computational graph is available. We evaluate these techniques on both MNIST digits and Omniglot handwritten characters. In the case of MNIST digits, we show that projections into the latent space maintain information about the style and the identity of the digit. In the case of Omniglot characters, we show that even characters from alphabets that have not been seen during training may be projected well into the latent space; this suggests that this approach may have applications in one-shot learning.

##### Abstract (translated by Google)
生成对抗网络（GAN）学会通过将从潜在空间抽取的样本通过生成网络从高维分布合成新样本。当高维分布描述特定数据集的图像时，网络应该学习为在潜在空间中彼此接近的潜在变量产生视觉上相似的图像样本。对于诸如图像检索和图像分类之类的任务，通过将图像投影到潜在空间中来利用潜在空间的排列，并将其用作区分性任务的表示可能是有用的。 GAN通常由多层非线性计算组成，使得它们很难反转。本文介绍了使用任何预先训练的GAN将图像样本投影到潜在空间的技术，只要计算图是可用的。我们在MNIST数字和Omniglot手写字符上评估这些技术。在MNIST数字的情况下，我们显示对潜在空间的投影保持关于数字的风格和身份的信息。在Omniglot字符的情况下，我们表明即使是在训练期间没有看到的字母的字符也可以很好地投影到潜在空间中;这表明这种方法可能在一次性学习中有应用。

##### URL
[https://arxiv.org/abs/1611.05644](https://arxiv.org/abs/1611.05644)

##### PDF
[https://arxiv.org/pdf/1611.05644](https://arxiv.org/pdf/1611.05644)

