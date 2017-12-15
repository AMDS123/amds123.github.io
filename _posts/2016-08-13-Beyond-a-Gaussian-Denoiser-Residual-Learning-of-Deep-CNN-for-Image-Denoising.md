---
layout: post
title: "Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising"
date: 2016-08-13 13:33:28
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Attention CNN
author: Kai Zhang, Wangmeng Zuo, Yunjin Chen, Deyu Meng, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative model learning for image denoising has been recently attracting considerable attentions due to its favorable denoising performance. In this paper, we take one step forward by investigating the construction of feed-forward denoising convolutional neural networks (DnCNNs) to embrace the progress in very deep architecture, learning algorithm, and regularization method into image denoising. Specifically, residual learning and batch normalization are utilized to speed up the training process as well as boost the denoising performance. Different from the existing discriminative denoising models which usually train a specific model for additive white Gaussian noise (AWGN) at a certain noise level, our DnCNN model is able to handle Gaussian denoising with unknown noise level (i.e., blind Gaussian denoising). With the residual learning strategy, DnCNN implicitly removes the latent clean image in the hidden layers. This property motivates us to train a single DnCNN model to tackle with several general image denoising tasks such as Gaussian denoising, single image super-resolution and JPEG image deblocking. Our extensive experiments demonstrate that our DnCNN model can not only exhibit high effectiveness in several general image denoising tasks, but also be efficiently implemented by benefiting from GPU computing.

##### Abstract (translated by Google)
图像去噪的辨识模型学习近年来受到了相当的关注，因为它具有良好的去噪性能。在本文中，我们通过研究前馈降噪卷积神经网络（DnCNNs）的构建向前迈进了一步，将深度架构，学习算法和正则化方法的进展融入到图像去噪中。具体来说，利用残留学习和批量归一化来加快训练过程并提高去噪性能。不同于通常训练一定噪声水平下的加性高斯白噪声（AWGN）的特定模型的现有鉴别降噪模型，我们的DnCNN模型能够处理未知噪声水平（即，高斯去噪）的高斯去噪。通过残留学习策略，DnCNN隐式地去除隐藏层中的潜在干净图像。这个属性激励我们训练一个单一的DnCNN模型来解决一些通用的图像去噪任务，如高斯去噪，单幅图像超分辨率和JPEG图像去块。我们广泛的实验表明，我们的DnCNN模型不仅能够在几个一般的图像去噪任务中表现出高效率，而且可以通过受益于GPU计算而有效地实现。

##### URL
[https://arxiv.org/abs/1608.03981](https://arxiv.org/abs/1608.03981)

##### PDF
[https://arxiv.org/pdf/1608.03981](https://arxiv.org/pdf/1608.03981)

