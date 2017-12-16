---
layout: post
title: "ShiftCNN: Generalized Low-Precision Architecture for Inference of Convolutional Neural Networks"
date: 2017-06-07 22:00:25
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Denis A. Gudovskiy, Luca Rigazio
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce ShiftCNN, a generalized low-precision architecture for inference of multiplierless convolutional neural networks (CNNs). ShiftCNN is based on a power-of-two weight representation and, as a result, performs only shift and addition operations. Furthermore, ShiftCNN substantially reduces computational cost of convolutional layers by precomputing convolution terms. Such an optimization can be applied to any CNN architecture with a relatively small codebook of weights and allows to decrease the number of product operations by at least two orders of magnitude. The proposed architecture targets custom inference accelerators and can be realized on FPGAs or ASICs. Extensive evaluation on ImageNet shows that the state-of-the-art CNNs can be converted without retraining into ShiftCNN with less than 1% drop in accuracy when the proposed quantization algorithm is employed. RTL simulations, targeting modern FPGAs, show that power consumption of convolutional layers is reduced by a factor of 4 compared to conventional 8-bit fixed-point architectures.

##### Abstract (translated by Google)
在本文中，我们将介绍ShiftCNN，一种推广无乘法卷积神经网络（CNN）的广义低精度架构。 ShiftCNN基于两权的权重表示，因此仅执行移位和加法操作。此外，ShiftCNN通过预先计算卷积项大大降低了卷积层的计算成本。这样的优化可以应用于具有相对较小的权重码本的任何CNN架构，并且允许将产品操作的数量减少至少两个数量级。所提出的架构针对自定义推理加速器，可以在FPGA或ASIC上实现。对ImageNet的广泛评估表明，当采用所提出的量化算法时，可以转换最新的CNN，而不需要重新训练到ShiftCNN中，精度下降小于1％。针对现代FPGA的RTL仿真表明，与传统的8位定点架构相比，卷积层的功耗降低了4倍。

##### URL
[https://arxiv.org/abs/1706.02393](https://arxiv.org/abs/1706.02393)

##### PDF
[https://arxiv.org/pdf/1706.02393](https://arxiv.org/pdf/1706.02393)

