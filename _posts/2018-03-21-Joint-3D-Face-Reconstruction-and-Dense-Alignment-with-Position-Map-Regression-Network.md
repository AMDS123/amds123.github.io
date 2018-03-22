---
layout: post
title: "Joint 3D Face Reconstruction and Dense Alignment with Position Map Regression Network"
date: 2018-03-21 10:27:04
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Yao Feng, Fan Wu, Xiaohu Shao, Yanfeng Wang, Xi Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a straightforward method that simultaneously reconstructs the 3D facial structure and provides dense alignment. To achieve this, we design a 2D representation called UV position map which records the 3D shape of a complete face in UV space, then train a simple Convolutional Neural Network to regress it from a single 2D image. We also integrate a weight mask into the loss function during training to improve the performance of the network. Our method does not rely on any prior face model, and can reconstruct full facial geometry along with semantic meaning. Meanwhile, our network is very light-weighted and spends only 9.8ms to process an image, which is extremely faster than previous works. Experiments on multiple challenging datasets show that our method surpasses other state-of-the-art methods on both reconstruction and alignment tasks by a large margin.

##### Abstract (translated by Google)
我们提出了一种直接的方法，可以同时重建3D面部结构并提供密集的对齐。为了达到这个目的，我们设计了一个称为UV位置图的2D表示法，它记录了UV空间中一个完整人脸的三维形状，然后训练一个简单的卷积神经网络从单个2D图像中对其进行回归。我们还将训练期间的权重蒙版整合到损失函数中，以提高网络的性能。我们的方法不依赖于任何先前的人脸模型，并且可以重建具有语义含义的完整面部几何。同时，我们的网络非常轻量化，仅花费9.8ms处理图像，这比以前的作品要快得多。对多个具有挑战性的数据集进行的实验表明，我们的方法在重建和对齐任务上的优势远远超过其他最先进的方法。

##### URL
[http://arxiv.org/abs/1803.07835](http://arxiv.org/abs/1803.07835)

##### PDF
[http://arxiv.org/pdf/1803.07835](http://arxiv.org/pdf/1803.07835)

