---
layout: post
title: "Faster CNNs with Direct Sparse Convolutions and Guided Pruning"
date: 2017-07-28 22:26:27
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference
author: Jongsoo Park, Sheng Li, Wei Wen, Ping Tak Peter Tang, Hai Li, Yiran Chen, Pradeep Dubey
mathjax: true
---

* content
{:toc}

##### Abstract
Phenomenally successful in practical inference problems, convolutional neural networks (CNN) are widely deployed in mobile devices, data centers, and even supercomputers. The number of parameters needed in CNNs, however, are often large and undesirable. Consequently, various methods have been developed to prune a CNN once it is trained. Nevertheless, the resulting CNNs offer limited benefits. While pruning the fully connected layers reduces a CNN's size considerably, it does not improve inference speed noticeably as the compute heavy parts lie in convolutions. Pruning CNNs in a way that increase inference speed often imposes specific sparsity structures, thus limiting the achievable sparsity levels. We present a method to realize simultaneously size economy and speed improvement while pruning CNNs. Paramount to our success is an efficient general sparse-with-dense matrix multiplication implementation that is applicable to convolution of feature maps with kernels of arbitrary sparsity patterns. Complementing this, we developed a performance model that predicts sweet spots of sparsity levels for different layers and on different computer architectures. Together, these two allow us to demonstrate 3.1--7.3$\times$ convolution speedups over dense convolution in AlexNet, on Intel Atom, Xeon, and Xeon Phi processors, spanning the spectrum from mobile devices to supercomputers. We also open source our project at this https URL

##### Abstract (translated by Google)
卷积神经网络（CNN）在实际推理问题中显得成功，在移动设备，数据中心甚至超级计算机中广泛使用。然而，CNN所需的参数数量往往很大，并且是不希望的。因此，一旦训练有素的CNN，各种方法已经被开发出来。不过，由此产生的CNN提供的利益有限。虽然修剪完全连接的层会大大减小CNN的大小，但不会显着提高推理速度，因为计算较重的部分位于卷积中。以增加推理速度的方式修剪CNN通常会施加特定的稀疏结构，从而限制了可实现的稀疏水平。我们提出一种同时实现规模经济和速度提升的方法，同时修剪CNN。最重要的是我们的成功是一个高效的一般稀疏矩阵乘法实现，适用于特征映射与任意稀疏模式的核的卷积。为了补充这一点，我们开发了一个性能模型，可以预测不同层次和不同计算机体系结构的稀疏水平的甜点。通过这两者，我们可以在AlexNet，Intel Atom，Xeon和Xeon Phi处理器的密集卷积中演示3.1〜7.3倍的卷积加速，从移动设备到超级计算机。我们也在这个https网址上开源我们的项目

##### URL
[https://arxiv.org/abs/1608.01409](https://arxiv.org/abs/1608.01409)

##### PDF
[https://arxiv.org/pdf/1608.01409](https://arxiv.org/pdf/1608.01409)

