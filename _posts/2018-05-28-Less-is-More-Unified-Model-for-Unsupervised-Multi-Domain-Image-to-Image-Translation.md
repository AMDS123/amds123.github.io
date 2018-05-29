---
layout: post
title: "Less is More: Unified Model for Unsupervised Multi-Domain Image-to-Image Translation"
date: 2018-05-28 11:29:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Style_Transfer
author: Xiao Liu, Shengchuan Zhang, Hong Liu, Xin Liu, Rongrong Ji
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we aim at solving the multi-domain image-to-image translation problem by a single GAN-based model in an unsupervised manner. In the field of image-to-image translation, most previous works mainly focus on adopting a generative adversarial network, which contains three parts, i.e., encoder, decoder and discriminator. These three parts are trained to give the encoder and the decoder together as a translator. However, the discriminator that occupies a lot of parameters is abandoned after the training process, which is wasteful of computation and memory. To handle this problem, we integrate the discriminator and the encoder of the traditional framework into a single network, where the decoder in our framework translates the information encoded by the discriminator to the target image. As a result, our framework only contains two parts, i.e., decoder and discriminator, which effectively reduces the number of the parameters of the network and achieves more effective training. Then, we expand the traditional binary-class discriminator to the multi-classes discriminator, which solves the multi-domain image-to-image translation problem in traditional settings. At last, we propose the label encoder to transform the label vector to high-dimension representation automatically rather than designing a one-hot vector manually. We performed extensive experiments on many image-to-image translation tasks including style transfer, season transfer, face hallucination, etc. A unified model was trained to translate images sampled from 14 considerable different domains and the comparisons to several recently-proposed approaches demonstrate the superiority and novelty of our framework.

##### Abstract (translated by Google)
在本文中，我们旨在通过单个基于GAN的模型以无监督的方式解决多领域图像到图像的转换问题。在图像到图像的翻译领域，大部分以前的工作主要集中在采用生成对抗网络，该网络包含三部分，即编码器，解码器和鉴别器。这三部分经过训练，可以将编码器和解码器作为翻译器一起使用。然而，在训练过程之后，占用大量参数的鉴别器被放弃，这是计算和存储的浪费。为了解决这个问题，我们将传统框架的鉴别器和编码器集成到一个网络中，我们的框架中的解码器将鉴别器编码的信息转换为目标图像。因此，我们的框架只包含两部分，即解码器和鉴别器，这有效地减少了网络参数的数量，并且实现了更有效的训练。然后，将传统的二进制类鉴别器扩展为多类鉴别器，解决了传统设置中的多域图像到图像转换问题。最后，我们提出了标签编码器来自动将标签向量转换为高维表示，而不是手动设计一个热点向量。我们对许多图像到图像的翻译任务进行了广泛的实验，包括样式转换，季节转换，面部幻觉等。统一模型被训练以翻译从14个相当不同领域采样的图像，并且比较了几个最近提出的方法，我们的框架的优势和新颖性。

##### URL
[http://arxiv.org/abs/1805.10871](http://arxiv.org/abs/1805.10871)

##### PDF
[http://arxiv.org/pdf/1805.10871](http://arxiv.org/pdf/1805.10871)

