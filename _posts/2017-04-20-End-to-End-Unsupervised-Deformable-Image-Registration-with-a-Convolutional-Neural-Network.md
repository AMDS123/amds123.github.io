---
layout: post
title: "End-to-End Unsupervised Deformable Image Registration with a Convolutional Neural Network"
date: 2017-04-20 09:40:50
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Bob D. de Vos, Floris F. Berendsen, Max A. Viergever, Marius Staring, Ivana Išgum
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a deep learning network for deformable image registration (DIRNet). The DIRNet consists of a convolutional neural network (ConvNet) regressor, a spatial transformer, and a resampler. The ConvNet analyzes a pair of fixed and moving images and outputs parameters for the spatial transformer, which generates the displacement vector field that enables the resampler to warp the moving image to the fixed image. The DIRNet is trained end-to-end by unsupervised optimization of a similarity metric between input image pairs. A trained DIRNet can be applied to perform registration on unseen image pairs in one pass, thus non-iteratively. Evaluation was performed with registration of images of handwritten digits (MNIST) and cardiac cine MR scans (Sunnybrook Cardiac Data). The results demonstrate that registration with DIRNet is as accurate as a conventional deformable image registration method with substantially shorter execution times.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个深度学习网络可变形图像注册（DIRNet）。 DIRNet由卷积神经网络（ConvNet）回归器，空间变换器和重采样器组成。 ConvNet分析一对固定的和移动的图像并输出空间变换器的参数，其产生位移矢量场，使得重采样器能够将运动图像变形为固定图像。 DIRNet通过无监督地优化输入图像对之间的相似性度量来端对端地进行训练。一个训练有素的DIRNet可以用来在一个通道上执行不可见的图像对的注册，因此是非迭代的。手术数字（MNIST）和心脏电影MR扫描（Sunnybrook心脏数据）的图像的登记进行评估。结果表明，使用DIRNet进行注册与传统的可变形图像配准方法一样准确，执行时间大大缩短。

##### URL
[https://arxiv.org/abs/1704.06065](https://arxiv.org/abs/1704.06065)

##### PDF
[https://arxiv.org/pdf/1704.06065](https://arxiv.org/pdf/1704.06065)

