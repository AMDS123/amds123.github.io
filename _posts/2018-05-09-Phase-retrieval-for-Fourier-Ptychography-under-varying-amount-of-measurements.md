---
layout: post
title: "Phase retrieval for Fourier Ptychography under varying amount of measurements"
date: 2018-05-09 15:42:44
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Lokesh Boominathan, Mayug Maniparambil, Honey Gupta, Rahul Baburajan, Kaushik Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
Fourier Ptychography is a recently proposed imaging technique that yields high-resolution images by computationally transcending the diffraction blur of an optical system. At the crux of this method is the phase retrieval algorithm, which is used for computationally stitching together low-resolution images taken under varying illumination angles of a coherent light source. However, the traditional iterative phase retrieval technique relies heavily on the initialization and also need a good amount of overlap in the Fourier domain for the successively captured low-resolution images, thus increasing the acquisition time and data. We show that an auto-encoder based architecture can be adaptively trained for phase retrieval under both low overlap, where traditional techniques completely fail, and at higher levels of overlap. For the low overlap case we show that a supervised deep learning technique using an autoencoder generator is a good choice for solving the Fourier ptychography problem. And for the high overlap case, we show that optimizing the generator for reducing the forward model error is an appropriate choice. Using simulations for the challenging case of uncorrelated phase and amplitude, we show that our method outperforms many of the previously proposed Fourier ptychography phase retrieval techniques.

##### Abstract (translated by Google)
Fourier Ptychography是最近提出的一种成像技术，它通过计算超越光学系统的衍射模糊来产生高分辨率图像。这种方法的关键在于相位检索算法，该算法用于将在相干光源的变化照明角度下拍摄的低分辨率图像进行计算拼接。然而，传统的迭代相位检索技术在很大程度上依赖于初始化，并且在傅里叶域中需要大量重叠以用于连续捕获的低分辨率图像，因此增加了采集时间和数据。我们表明，基于自动编码器的架构可以自适应地进行相位检索训练，在低重叠和传统技术完全失败的情况下，以及更高级别的重叠。对于低重叠情况，我们表明使用自编码发生器的有监督深度学习技术是解决傅立叶印迹问题的好选择。对于高重叠情况，我们表明优化发生器以减少正向模型误差是一个合适的选择。使用模拟来处理不相关的相位和振幅的具有挑战性的情况，我们表明，我们的方法胜过了许多先前提出的傅立叶心电图相位检索技术。

##### URL
[http://arxiv.org/abs/1805.03593](http://arxiv.org/abs/1805.03593)

##### PDF
[http://arxiv.org/pdf/1805.03593](http://arxiv.org/pdf/1805.03593)

