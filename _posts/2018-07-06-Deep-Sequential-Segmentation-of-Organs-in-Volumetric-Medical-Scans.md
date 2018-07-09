---
layout: post
title: "Deep Sequential Segmentation of Organs in Volumetric Medical Scans"
date: 2018-07-06 14:48:04
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN RNN
author: Alexey Novikov, David Major, Maria Wimmer, Dimitrios Lenis, Katja B&#xfc;hler
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation in 3D scans is playing an increasingly important role in current clinical practice supporting diagnosis, tissue quantification, or treatment planning. The current 3D approaches based on CNN usually suffer from at least three main issues caused predominantly by implementation constraints - first, they require resizing the volume to the lower-resolutional reference dimensions, second, the capacity of such approaches is very limited due to memory restrictions, and third, all slices of volumes have to be available at any given training or testing time. We address these problems by a U-Net-like architecture consisting of bidirectional Convolutional LSTM and convolutional, pooling, upsampling and concatenation layers enclosed into time-distributed wrappers. Our network can either process the full volumes in a sequential manner, or segment slabs of slices on demand. We demonstrate performance of our architecture on vertebrae and liver segmentation tasks in 3D CT scans.

##### Abstract (translated by Google)
3D扫描中的分割在支持诊断，组织定量或治疗计划的当前临床实践中发挥越来越重要的作用。目前基于CNN的3D方法通常至少受到三个主要问题的影响，主要是由于实施限制 - 首先，它们需要将音量调整到较低分辨率的参考尺寸;其次，由于存储器限制，这种方法的容量非常有限第三，在任何给定的培训或测试时间内，所有卷片都必须可用。我们通过类似U-Net的体系结构来解决这些问题，该体系结构包括双向卷积LSTM以及封装在时间分布包装器中的卷积，池化，上采样和连接层。我们的网络可以按顺序处理整个卷，也可以按需分割切片。我们展示了我们在3D CT扫描中对椎骨和肝脏分割任务的体系结构的表现。

##### URL
[http://arxiv.org/abs/1807.02437](http://arxiv.org/abs/1807.02437)

##### PDF
[http://arxiv.org/pdf/1807.02437](http://arxiv.org/pdf/1807.02437)

