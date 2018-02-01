---
layout: post
title: "ConvCSNet: A Convolutional Compressive Sensing Framework Based on Deep Learning"
date: 2018-01-31 08:22:53
categories: arXiv_CV
tags: arXiv_CV Attention CNN Deep_Learning
author: Xiaotong Lu, Weisheng Dong, Peiyao Wang, Guangming Shi, Xuemei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Compressive sensing (CS), aiming to reconstruct an image/signal from a small set of random measurements has attracted considerable attentions in recent years. Due to the high dimensionality of images, previous CS methods mainly work on image blocks to avoid the huge requirements of memory and computation, i.e., image blocks are measured with Gaussian random matrices, and the whole images are recovered from the reconstructed image blocks. Though efficient, such methods suffer from serious blocking artifacts. In this paper, we propose a convolutional CS framework that senses the whole image using a set of convolutional filters. Instead of reconstructing individual blocks, the whole image is reconstructed from the linear convolutional measurements. Specifically, the convolutional CS is implemented based on a convolutional neural network (CNN), which performs both the convolutional CS and nonlinear reconstruction. Through end-to-end training, the sensing filters and the reconstruction network can be jointly optimized. To facilitate the design of the CS reconstruction network, a novel two-branch CNN inspired from a sparsity-based CS reconstruction model is developed. Experimental results show that the proposed method substantially outperforms previous state-of-the-art CS methods in term of both PSNR and visual quality.

##### Abstract (translated by Google)
压缩感知（CS）旨在从一小组随机测量重建图像/信号近年来引起了相当大的关注。由于图像的高维性，以前的CS方法主要是针对图像块进行处理，以避免对存储和计算的巨大需求，即用高斯随机矩阵来测量图像块，并且从重建的图像块中恢复整个图像。尽管有效，但这样的方法遭受严重的阻塞伪影。在本文中，我们提出了一个卷积CS框架，使用一组卷积滤波器来检测整个图像。整个图像是从线性卷积测量中重建出来的，而不是重建各个块。具体而言，卷积CS是基于卷积神经网络（CNN）实现的，该卷积神经网络执行卷积CS和非线性重构。通过端到端的培训，可以对传感滤波器和重构网络进行联合优化。为了便于CS重建网络的设计，开发了一种基于稀疏性CS重建模型的新型双分支CNN。实验结果表明，所提出的方法在PSNR和视觉质量方面均大大优于先前的CS方法。

##### URL
[http://arxiv.org/abs/1801.10342](http://arxiv.org/abs/1801.10342)

##### PDF
[http://arxiv.org/pdf/1801.10342](http://arxiv.org/pdf/1801.10342)

