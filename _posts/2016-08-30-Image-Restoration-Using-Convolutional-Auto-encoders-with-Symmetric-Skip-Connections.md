---
layout: post
title: "Image Restoration Using Convolutional Auto-encoders with Symmetric Skip Connections"
date: 2016-08-30 08:50:51
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Xiao-Jiao Mao, Chunhua Shen, Yu-Bin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image restoration, including image denoising, super resolution, inpainting, and so on, is a well-studied problem in computer vision and image processing, as well as a test bed for low-level image modeling algorithms. In this work, we propose a very deep fully convolutional auto-encoder network for image restoration, which is a encoding-decoding framework with symmetric convolutional-deconvolutional layers. In other words, the network is composed of multiple layers of convolution and de-convolution operators, learning end-to-end mappings from corrupted images to the original ones. The convolutional layers capture the abstraction of image contents while eliminating corruptions. Deconvolutional layers have the capability to upsample the feature maps and recover the image details. To deal with the problem that deeper networks tend to be more difficult to train, we propose to symmetrically link convolutional and deconvolutional layers with skip-layer connections, with which the training converges much faster and attains better results.

##### Abstract (translated by Google)
包括图像去噪，超分辨率修复，图像修复等在内的图像修复是计算机视觉和图像处理领域一个深入研究的问题，也是低层图像建模算法的测试平台。在这项工作中，我们提出了一个非常深的完全卷积自动编码器网络的图像恢复，这是一个编码解码框架与对称卷积去卷积层。换句话说，网络由多层卷积和解卷积算子组成，学习从损坏图像到原始图像的端到端映射。卷积层捕获图像内容的抽象，同时消除腐败。解卷积层能够对特征映射进行上采样并恢复图像细节。为了解决深层网络难以训练的问题，我们提出将卷积层和去卷积层与跳层连接进行对称连接，训练收敛速度更快，效果更好。

##### URL
[https://arxiv.org/abs/1606.08921](https://arxiv.org/abs/1606.08921)

##### PDF
[https://arxiv.org/pdf/1606.08921](https://arxiv.org/pdf/1606.08921)

