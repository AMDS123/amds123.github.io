---
layout: post
title: "Concurrent Spatial and Channel Squeeze & Excitation in Fully Convolutional Networks"
date: 2018-03-07 10:22:06
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Image_Classification Classification
author: Abhijit Guha Roy, Nassir Navab, Christian Wachinger
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional neural networks (F-CNNs) have set the state-of-the-art in image segmentation for a plethora of applications. Architectural innovations within F-CNNs have mainly focused on improving spatial encoding or network connectivity to aid gradient flow. In this paper, we explore an alternate direction of recalibrating the feature maps adaptively, to boost meaningful features, while suppressing weak ones. We draw inspiration from the recently proposed squeeze &amp; excitation (SE) module for channel recalibration of feature maps for image classification. Towards this end, we introduce three variants of SE modules for image segmentation, (i) squeezing spatially and exciting channel-wise (cSE), (ii) squeezing channel-wise and exciting spatially (sSE) and (iii) concurrent spatial and channel squeeze &amp; excitation (scSE). We effectively incorporate these SE modules within three different state-of-the-art F-CNNs (DenseNet, SD-Net, U-Net) and observe consistent improvement of performance across all architectures, while minimally effecting model complexity. Evaluations are performed on two challenging applications: whole brain segmentation on MRI scans (Multi-Atlas Labelling Challenge Dataset) and organ segmentation on whole body contrast enhanced CT scans (Visceral Dataset).

##### Abstract (translated by Google)
完全卷积神经网络（F-CNN）为大量应用设置了最先进的图像分割技术。 F-CNN中的建筑创新主要集中在改善空间编码或网络连接性以帮助梯度流动。在本文中，我们探讨了自适应地重新校准特征地图的替代方向，以提高有意义的特征，同时抑制弱特征。我们从最近提出的挤压＆amp;激励（SE）模块，用于图像分类的特征图的通道重新校准。为此，我们引入了用于图像分割的SE模块的三种变体，（i）压缩空间和激发通道方式（cSE），（ii）压缩通道方式和空间激励（sSE）和（iii）并发空间和通道挤压＆amp;激励（scSE）。我们有效地将这些SE模块合并到三个不同的最先进的F-CNN（DenseNet，SD-Net，U-Net）中，并观察到所有架构的性能持续改进，同时最小化了模型的复杂性。对两个具有挑战性的应用进行评估：MRI扫描（Multi-Atlas Labeling Challenge Dataset）上的全脑分割和全身对比增强CT扫描（Visceral Dataset）上的器官分割。

##### URL
[http://arxiv.org/abs/1803.02579](http://arxiv.org/abs/1803.02579)

##### PDF
[http://arxiv.org/pdf/1803.02579](http://arxiv.org/pdf/1803.02579)

