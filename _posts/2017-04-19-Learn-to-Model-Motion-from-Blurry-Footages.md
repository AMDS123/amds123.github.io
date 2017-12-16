---
layout: post
title: "Learn to Model Motion from Blurry Footages"
date: 2017-04-19 16:54:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Wenbin Li, Da Chen, Zhihan Lv, Yan Yan, Darren Cosker
mathjax: true
---

* content
{:toc}

##### Abstract
It is difficult to recover the motion field from a real-world footage given a mixture of camera shake and other photometric effects. In this paper we propose a hybrid framework by interleaving a Convolutional Neural Network (CNN) and a traditional optical flow energy. We first conduct a CNN architecture using a novel learnable directional filtering layer. Such layer encodes the angle and distance similarity matrix between blur and camera motion, which is able to enhance the blur features of the camera-shake footages. The proposed CNNs are then integrated into an iterative optical flow framework, which enable the capability of modelling and solving both the blind deconvolution and the optical flow estimation problems simultaneously. Our framework is trained end-to-end on a synthetic dataset and yields competitive precision and performance against the state-of-the-art approaches.

##### Abstract (translated by Google)
鉴于相机抖动和其他光度效应的混合，从真实世界的镜头恢复运动场是很困难的。在本文中，我们提出了一种交织卷积神经网络（CNN）和传统光流能量的混合框架。我们首先使用一种新颖的可学习定向滤波层来进行CNN架构。这种图层编码模糊和相机运动之间的角度和距离相似性矩阵，这可以增强相机抖动的模糊特征。然后将所提出的CNN集成到迭代光流框架中，从而能够同时建模和解决盲解卷积和光流估计问题。我们的框架是在一个综合数据集上进行端到端的培训，并针对最先进的方法提供有竞争力的精度和性能。

##### URL
[https://arxiv.org/abs/1704.05817](https://arxiv.org/abs/1704.05817)

##### PDF
[https://arxiv.org/pdf/1704.05817](https://arxiv.org/pdf/1704.05817)

