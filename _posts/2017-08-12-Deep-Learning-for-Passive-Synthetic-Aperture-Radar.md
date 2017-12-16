---
layout: post
title: "Deep Learning for Passive Synthetic Aperture Radar"
date: 2017-08-12 00:25:10
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization RNN Deep_Learning Gradient_Descent
author: Bariscan Yonel, Eric Mason, Birsen Yazıcı
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a deep learning (DL) framework for inverse problems in imaging, and demonstrate the advantages and applicability of this approach in passive synthetic aperture radar (SAR) image reconstruction. We interpret image recon- struction as a machine learning task and utilize deep networks as forward and inverse solvers for imaging. Specifically, we design a recurrent neural network (RNN) architecture as an inverse solver based on the iterations of proximal gradient descent optimization methods. We further adapt the RNN architecture to image reconstruction problems by transforming the network into a recurrent auto-encoder, thereby allowing for unsupervised training. Our DL based inverse solver is particularly suitable for a class of image formation problems in which the forward model is only partially known. The ability to learn forward models and hyper parameters combined with unsupervised training approach establish our recurrent auto-encoder suitable for real world applications. We demonstrate the performance of our method in passive SAR image reconstruction. In this regime a source of opportunity, with unknown location and transmitted waveform, is used to illuminate a scene of interest. We investigate recurrent auto- encoder architecture based on the 1 and 0 constrained least- squares problem. We present a projected stochastic gradient descent based training scheme which incorporates constraints of the unknown model parameters. We demonstrate through extensive numerical simulations that our DL based approach out performs conventional sparse coding methods in terms of computation and reconstructed image quality, specifically, when no information about the transmitter is available.

##### Abstract (translated by Google)
我们引入了深度学习（DL）框架来解决成像中的反问题，并展示了这种方法在被动合成孔径雷达（SAR）图像重建中的优势和适用性。我们将图像重构解释为机器学习任务，并利用深度网络作为正向和反向解算器进行成像。具体而言，我们基于近端梯度下降优化方法的迭代，设计递归神经网络（RNN）架构作为逆求解器。我们进一步适应RNN体系结构的图像重建问题，将网络转换成一个循环自动编码器，从而允许无监督的训练。我们的基于DL的逆向求解器特别适合于一类图像形成问题，其中正演模型只是部分已知的。学习正向模型和超参数以及无监督训练方法的能力建立了适合现实世界应用的经常性自动编码器。我们证明了我们的方法在被动SAR图像重建中的性能。在这个机制中，一个机会的来源，具有未知的位置和传输的波形，被用来照亮一个感兴趣的场景。我们调查基于1和0约束最小二乘问题的经常性自动编码器体系结构。我们提出了一个投影随机梯度下降的训练方案，它包含了未知模型参数的约束条件。我们通过大量的数值模拟演示，我们的基于DL的方法在计算和重构图像质量方面执行传统的稀疏编码方法，具体地，当没有关于发射机的信息可用时。

##### URL
[https://arxiv.org/abs/1708.04682](https://arxiv.org/abs/1708.04682)

##### PDF
[https://arxiv.org/pdf/1708.04682](https://arxiv.org/pdf/1708.04682)

