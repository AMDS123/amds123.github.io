---
layout: post
title: "DCFNet: Discriminant Correlation Filters Network for Visual Tracking"
date: 2017-04-13 10:08:14
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Image_Classification Object_Tracking Classification Relation
author: Qiang Wang, Jin Gao, Junliang Xing, Mengdan Zhang, Weiming Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminant Correlation Filters (DCF) based methods now become a kind of dominant approach to online object tracking. The features used in these methods, however, are either based on hand-crafted features like HoGs, or convolutional features trained independently from other tasks like image classification. In this work, we present an end-to-end lightweight network architecture, namely DCFNet, to learn the convolutional features and perform the correlation tracking process simultaneously. Specifically, we treat DCF as a special correlation filter layer added in a Siamese network, and carefully derive the backpropagation through it by defining the network output as the probability heatmap of object location. Since the derivation is still carried out in Fourier frequency domain, the efficiency property of DCF is preserved. This enables our tracker to run at more than 60 FPS during test time, while achieving a significant accuracy gain compared with KCF using HoGs. Extensive evaluations on OTB-2013, OTB-2015, and VOT2015 benchmarks demonstrate that the proposed DCFNet tracker is competitive with several state-of-the-art trackers, while being more compact and much faster.

##### Abstract (translated by Google)
基于判别相关滤波器（DCF）的方法现在成为一种在线对象跟踪的主导方法。然而，这些方法中使用的特征要么基于HoG等手工特征，要么独立于其他任务（如图像分类）训练的卷积特征。在这项工作中，我们提出了一个端到端的轻量级网络体系结构，即DCFNet，来学习卷积特征并同时执行相关性跟踪过程。具体来说，我们将DCF作为一个在连体网络中添加的特殊相关滤波器层，并通过将网络输出定义为目标位置的概率热图来仔细推导反向传播。由于导数仍然在傅立叶频域进行，所以DCF的效率特性得以保留。这使我们的跟踪器在测试时间内可以以超过60 FPS的速度运行，同时与使用HoG的KCF相比，实现了显着的准确度增益。对OTB-2013，OTB-2015和VOT2015基准的广泛评估表明，所提议的DCFNet跟踪器与多个最先进的跟踪器相比具有竞争力，同时更紧凑，更快。

##### URL
[https://arxiv.org/abs/1704.04057](https://arxiv.org/abs/1704.04057)

##### PDF
[https://arxiv.org/pdf/1704.04057](https://arxiv.org/pdf/1704.04057)

