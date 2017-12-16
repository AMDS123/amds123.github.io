---
layout: post
title: "Compressed Sensing MRI Reconstruction with Cyclic Loss in Generative Adversarial Networks"
date: 2017-09-03 18:08:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Deep_Learning
author: Tran Minh Quan, Thanh Nguyen-Duc, Won-Ki Jeong
mathjax: true
---

* content
{:toc}

##### Abstract
Compressed Sensing MRI (CS-MRI) has provided theoretical foundations upon which the time-consuming MRI acquisition process can be accelerated. However, it primarily relies on iterative numerical solvers which still hinders their adaptation in time-critical applications. In addition, recent advances in deep neural networks have shown their potential in computer vision and image processing, but their adaptation to MRI reconstruction is still in an early stage. In this paper, we propose a novel deep learning-based generative adversarial model, RefineGAN, for fast and accurate CS-MRI reconstruction. The proposed model is a variant of fully-residual convolutional autoencoder and generative adversarial networks (GANs), specifically designed for CS-MRI formulation; it employs deeper generator and discriminator networks with cyclic data consistency loss for faithful interpolation in the given under-sampled k-space data. In addition, our solution leverages a chained network to further enhance the reconstruction quality. RefineGAN is fast and accurate - the reconstruction process is extremely rapid, as low as tens of milliseconds for reconstruction of a 256 x 256 image, because it is one-way deployment on a feedforward network, and the image quality is superior even for extremely low sampling rate (as low as 10%) due to the data-driven nature of the method. We demonstrate that RefineGAN outperforms the state-of-the-art CS-MRI methods by a large margin in terms of both running time and image quality via evaluation using several open-source MRI databases.

##### Abstract (translated by Google)
压缩感测MRI（CS-MRI）为加速耗时的MRI采集过程提供了理论基础。然而，它主要依赖迭代数值解算器，这仍然妨碍了它们在时间关键型应用中的适应性。另外，深度神经网络的最新进展已经显示了它们在计算机视觉和图像处理方面的潜力，但是它们对MRI重建的适应仍处于早期阶段。在本文中，我们提出了一个新的基于深度学习的生成对抗模型，RefineGAN，用于快速和准确的CS-MRI重建。该模型是完全残差卷积自动编码器和生成对抗网络（GAN）的变体，专门为CS-MRI制定而设计;它采用更深的发生器和鉴别器网络，在给定的欠采样k空间数据中进行忠实的插值。另外，我们的解决方案利用链接网络来进一步提高重建质量。 RefineGAN快速准确 - 重建过程非常迅速，重建256x256图像的重建过程非常快，几十毫秒，因为它是前向网络的单向部署，即使是极低的图像质量也是优越的采样率（低至10％）由于该方法的数据驱动性质。我们通过使用多个开源MRI数据库进行评估，证明了RefineGAN在运行时间和图像质量方面都优于最先进的CS-MRI方法。

##### URL
[https://arxiv.org/abs/1709.00753](https://arxiv.org/abs/1709.00753)

##### PDF
[https://arxiv.org/pdf/1709.00753](https://arxiv.org/pdf/1709.00753)

