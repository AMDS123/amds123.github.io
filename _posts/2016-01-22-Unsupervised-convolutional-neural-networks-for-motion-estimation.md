---
layout: post
title: "Unsupervised convolutional neural networks for motion estimation"
date: 2016-01-22 17:57:07
categories: arXiv_CV
tags: arXiv_CV CNN
author: Aria Ahmadi, Ioannis Patras
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional methods for motion estimation estimate the motion field F between a pair of images as the one that minimizes a predesigned cost function. In this paper, we propose a direct method and train a Convolutional Neural Network (CNN) that when, at test time, is given a pair of images as input it produces a dense motion field F at its output layer. In the absence of large datasets with ground truth motion that would allow classical supervised training, we propose to train the network in an unsupervised manner. The proposed cost function that is optimized during training, is based on the classical optical flow constraint. The latter is differentiable with respect to the motion field and, therefore, allows backpropagation of the error to previous layers of the network. Our method is tested on both synthetic and real image sequences and performs similarly to the state-of-the-art methods.

##### Abstract (translated by Google)
用于运动估计的传统方法估计一对图像之间的运动场F，使得预先设计的成本函数最小化。在本文中，我们提出了一种直接的方法和训练一个卷积神经网络（CNN），当在测试时，给一对图像作为输入，它在输出层产生一个密集的运动场F.在没有大量数据集的地面真实运动将允许经典的监督训练，我们建议训练网络以无监督的方式。所提出的在训练期间优化的成本函数是基于经典光流约束的。后者在运动场方面是可区分的，因此，允许将误差反向传播到网络的前一层。我们的方法在合成和真实的图像序列上进行了测试，并且与最先进的方法类似。

##### URL
[https://arxiv.org/abs/1601.06087](https://arxiv.org/abs/1601.06087)

##### PDF
[https://arxiv.org/pdf/1601.06087](https://arxiv.org/pdf/1601.06087)

