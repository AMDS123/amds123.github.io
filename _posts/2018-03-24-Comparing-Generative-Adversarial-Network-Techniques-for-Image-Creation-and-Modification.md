---
layout: post
title: "Comparing Generative Adversarial Network Techniques for Image Creation and Modification"
date: 2018-03-24 11:19:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face CNN
author: Mathijs Pieters, Marco Wiering
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) have demonstrated to be successful at generating realistic real-world images. In this paper we compare various GAN techniques, both supervised and unsupervised. The effects on training stability of different objective functions are compared. We add an encoder to the network, making it possible to encode images to the latent space of the GAN. The generator, discriminator and encoder are parameterized by deep convolutional neural networks. For the discriminator network we experimented with using the novel Capsule Network, a state-of-the-art technique for detecting global features in images. Experiments are performed using a digit and face dataset, with various visualizations illustrating the results. The results show that using the encoder network it is possible to reconstruct images. With the conditional GAN we can alter visual attributes of generated or encoded images. The experiments with the Capsule Network as discriminator result in generated images of a lower quality, compared to a standard convolutional neural network.

##### Abstract (translated by Google)
生成敌对网络（GAN）已经证明能够成功地生成逼真的真实世界图像。在本文中，我们比较了各种GAN技术，有监督和无监督。比较不同目标函数对训练稳定性的影响。我们在网络中添加一个编码器，使得可以将图像编码到GAN的潜在空间。发生器，鉴别器和编码器通过深度卷积神经网络进行参数化。对于鉴别器网络，我们使用新颖的胶囊网络进行实验，这是一种用于检测图像中全局特征的最新技术。使用数字和人脸数据集进行实验，并通过各种可视化来说明结果。结果显示使用编码器网络可以重建图像。使用条件GAN，我们可以改变生成或编码图像的视觉属性。与标准卷积神经网络相比，胶囊网络作为鉴别器的实验导致生成的图像质量较低。

##### URL
[https://arxiv.org/abs/1803.09093](https://arxiv.org/abs/1803.09093)

##### PDF
[https://arxiv.org/pdf/1803.09093](https://arxiv.org/pdf/1803.09093)

