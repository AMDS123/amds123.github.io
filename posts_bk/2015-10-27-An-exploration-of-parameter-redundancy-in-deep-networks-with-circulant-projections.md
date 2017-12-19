---
layout: post
title: "An exploration of parameter redundancy in deep networks with circulant projections"
date: 2015-10-27 06:45:51
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Yu Cheng, Felix X. Yu, Rogerio S. Feris, Sanjiv Kumar, Alok Choudhary, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the redundancy of parameters in deep neural networks by replacing the conventional linear projection in fully-connected layers with the circulant projection. The circulant structure substantially reduces memory footprint and enables the use of the Fast Fourier Transform to speed up the computation. Considering a fully-connected neural network layer with d input nodes, and d output nodes, this method improves the time complexity from O(d^2) to O(dlogd) and space complexity from O(d^2) to O(d). The space savings are particularly important for modern deep convolutional neural network architectures, where fully-connected layers typically contain more than 90% of the network parameters. We further show that the gradient computation and optimization of the circulant projections can be performed very efficiently. Our experiments on three standard datasets show that the proposed approach achieves this significant gain in storage and efficiency with minimal increase in error rate compared to neural networks with unstructured projections.

##### Abstract (translated by Google)
我们通过用循环投影代替完全连接层中的传统线性投影来探索深度神经网络中参数的冗余。循环结构大大减少了内存占用，并能够使用快速傅里叶变换来加速计算。考虑一个具有d个输入节点和d个输出节点的全连接神经网络层，该方法将时间复杂度从O（d ^ 2）提高到O（dlogd），空间复杂度由O（d ^ 2）提高到O ）。节省空间对于现代深度卷积神经网络架构特别重要，其中完全连接的层通常包含超过90％的网络参数。我们进一步表明，梯度计算和循环投影的优化可以非常有效地执行。我们在三个标准数据集上进行的实验表明，与具有非结构化投影的神经网络相比，所提出的方法在存储和效率方面实现了显着的增益，误差率增加最小。

##### URL
[https://arxiv.org/abs/1502.03436](https://arxiv.org/abs/1502.03436)

##### PDF
[https://arxiv.org/pdf/1502.03436](https://arxiv.org/pdf/1502.03436)

