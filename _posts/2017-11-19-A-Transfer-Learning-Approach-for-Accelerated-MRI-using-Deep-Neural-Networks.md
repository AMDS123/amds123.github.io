---
layout: post
title: "A Transfer-Learning Approach for Accelerated MRI using Deep Neural Networks"
date: 2017-11-19 17:34:35
categories: arXiv_CV
tags: arXiv_CV
author: Salman Ul Hassan Dar, Tolga Çukur
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network based architectures have recently been proposed for reconstruction of undersampled MR acquisitions. A deep network containing many free parameters is typically trained using a relatively large set of fully-sampled MRI data, and later used for on-line reconstruction of undersampled data. Ideally network performance should be optimized by drawing the training and testing data from the same domain. In practice, however, large datasets comprising hundreds of subjects scanned under a common protocol are rare. Here, we propose a transfer-learning approach to address the problem of data scarcity in training deep networks for accelerated MRI. The proposed approach trains neural networks using thousands of samples from a public dataset of natural images (ImageNet). The network is then fine-tuned using only few tens of MR images acquired in the testing domain (T1- or T2-weighted MRI). The ImageNet-trained network yields nearly identical reconstructions to networks trained directly in the testing domain using thousands of MR images, and it outperforms conventional compressed sensing reconstructions in terms of image quality. The proposed approach might facilitate the use of neural networks for MRI reconstruction without the need for collection of extensive imaging datasets.

##### Abstract (translated by Google)
最近已经提出了基于神经网络的架构来重建欠采样的MR采集。包含许多自由参数的深层网络通常使用相对较大的一组完整采样的MRI数据进行训练，随后用于在线重建欠采样数据。理想情况下，网络性能应该通过从同一个域中绘制训练和测试数据来优化。然而，在实践中，包含数百个在共同协议下扫描的受试者的大型数据集是罕见的。在这里，我们提出一种转移学习的方法来解决训练深度网络加速MRI数据稀缺的问题。所提出的方法使用来自自然图像（ImageNet）的公共数据集的数千个样本训练神经网络。然后使用在测试领域获得的数十个MR图像（T1或T2加权MRI）对网络进行微调。经ImageNet训练的网络对于使用数千个MR图像直接在测试域中训练的网络产生几乎相同的重构，并且其在图像质量方面优于传统的压缩感测重建。所提出的方法可能有助于使用神经网络进行MRI重建，而不需要收集大量的成像数据集。

##### URL
[https://arxiv.org/abs/1710.02615](https://arxiv.org/abs/1710.02615)

##### PDF
[https://arxiv.org/pdf/1710.02615](https://arxiv.org/pdf/1710.02615)

