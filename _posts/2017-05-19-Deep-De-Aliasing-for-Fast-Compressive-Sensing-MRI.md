---
layout: post
title: "Deep De-Aliasing for Fast Compressive Sensing MRI"
date: 2017-05-19 18:17:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Simiao Yu, Hao Dong, Guang Yang, Greg Slabaugh, Pier Luigi Dragotti, Xujiong Ye, Fangde Liu, Simon Arridge, Jennifer Keegan, David Firmin, Yike Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Fast Magnetic Resonance Imaging (MRI) is highly in demand for many clinical applications in order to reduce the scanning cost and improve the patient experience. This can also potentially increase the image quality by reducing the motion artefacts and contrast washout. However, once an image field of view and the desired resolution are chosen, the minimum scanning time is normally determined by the requirement of acquiring sufficient raw data to meet the Nyquist-Shannon sampling criteria. Compressive Sensing (CS) theory has been perfectly matched to the MRI scanning sequence design with much less required raw data for the image reconstruction. Inspired by recent advances in deep learning for solving various inverse problems, we propose a conditional Generative Adversarial Networks-based deep learning framework for de-aliasing and reconstructing MRI images from highly undersampled data with great promise to accelerate the data acquisition process. By coupling an innovative content loss with the adversarial loss our de-aliasing results are more realistic. Furthermore, we propose a refinement learning procedure for training the generator network, which can stabilise the training with fast convergence and less parameter tuning. We demonstrate that the proposed framework outperforms state-of-the-art CS-MRI methods, in terms of reconstruction error and perceptual image quality. In addition, our method can reconstruct each image in 0.22ms--0.37ms, which is promising for real-time applications.

##### Abstract (translated by Google)
快速磁共振成像（MRI）对于许多临床应用是高度需求的，以降低扫描成本并改善患者体验。这也可能通过减少运动伪影和对比度冲刷来增加图像质量。然而，一旦选择了图像视场和期望的分辨率，最小扫描时间通常由获取足够的原始数据以满足奈奎斯特 - 香农（Nyquist-Shannon）采样标准的要求来确定。压缩感知（CS）理论与MRI扫描序列设计完美匹配，图像重建所需的原始数据少得多。受深度学习解决各种反问题的最新进展的启发，我们提出了一种基于条件生成对抗网络的深度学习框架，用于对高度欠采样数据的MRI图像进行去混叠和重构，并有望加速数据采集过程。通过将创新内容损失与对抗性损失相结合，我们的去混叠效果更加逼真。此外，我们提出了一种训练发生器网络的细化学习过程，可以使训练稳定，收敛速度快，参数调整少。我们证明，在重建误差和感知图像质量方面，所提出的框架优于最先进的CS-MRI方法。此外，我们的方法可以在0.22ms  -  0.37ms的时间内重建每个图像，这对于实时应用是有希望的。

##### URL
[https://arxiv.org/abs/1705.07137](https://arxiv.org/abs/1705.07137)

##### PDF
[https://arxiv.org/pdf/1705.07137](https://arxiv.org/pdf/1705.07137)

