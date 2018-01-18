---
layout: post
title: "TernausNet: U-Net with VGG11 Encoder Pre-Trained on ImageNet for Image Segmentation"
date: 2018-01-17 16:49:10
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Vladimir Iglovikov, Alexey Shvets
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel-wise image segmentation is demanding task in computer vision. Classical U-Net architectures composed of encoders and decoders are very popular for segmentation of medical images, satellite images etc. Typically, neural network initialized with weights from a network pre-trained on a large data set like ImageNet shows better performance than those trained from scratch on a small dataset. In some practical applications, particularly in medicine and traffic safety, the accuracy of the models is of utmost importance. In this paper, we demonstrate how the U-Net type architecture can be improved by the use of the pre-trained encoder. Our code and corresponding pre-trained weights are publicly available at https://github.com/ternaus/TernausNet. We compare three weight initialization schemes: LeCun uniform, the encoder with weights from VGG11 and full network trained on the Carvana dataset. This network architecture was a part of the winning solution (1st out of 735) in the Kaggle: Carvana Image Masking Challenge.

##### Abstract (translated by Google)
像素级的图像分割对于计算机视觉来说是一项艰巨的任务。经典的由编码器和解码器组成的U-Net体系结构在医学图像，卫星图像等的分割中是非常流行的。一般来说，神经网络通过来自像ImageNet这样的大数据集的预先训练的网络的权重进行初始化，在小数据集上划伤。在一些实际应用中，特别是在医学和交通安全方面，模型的精确性是至关重要的。在本文中，我们演示如何通过使用预先训练的编码器来改善U-Net型架构。我们的代码和相应的预先训练的权重可在https://github.com/ternaus/TernausNet公开获得。我们比较三个权重初始化方案：LeCun uniform，来自VGG11的权重的编码器和在Carvana数据集上训练的全网络。这个网络架构是Kaggle：Carvana Image Masking Challenge中赢得解决方案的一部分（735中的第一个）。

##### URL
[http://arxiv.org/abs/1801.05746](http://arxiv.org/abs/1801.05746)

##### PDF
[http://arxiv.org/pdf/1801.05746](http://arxiv.org/pdf/1801.05746)

