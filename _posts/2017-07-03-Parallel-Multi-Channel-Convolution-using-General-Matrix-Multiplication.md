---
layout: post
title: "Parallel Multi Channel Convolution using General Matrix Multiplication"
date: 2017-07-03 12:43:10
categories: arXiv_CV
tags: arXiv_CV CNN
author: Aravind Vasudevan, Andrew Anderson, David Gregg
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have emerged as one of the most successful machine learning technologies for image and video processing. The most computationally intensive parts of CNNs are the convolutional layers, which convolve multi-channel images with multiple kernels. A common approach to implementing convolutional layers is to expand the image into a column matrix (im2col) and perform Multiple Channel Multiple Kernel (MCMK) convolution using an existing parallel General Matrix Multiplication (GEMM) library. This im2col conversion greatly increases the memory footprint of the input matrix and reduces data locality. In this paper we propose a new approach to MCMK convolution that is based on General Matrix Multiplication (GEMM), but not on im2col. Our algorithm eliminates the need for data replication on the input thereby enabling us to apply the convolution kernels on the input images directly. We have implemented several variants of our algorithm on a CPU processor and an embedded ARM processor. On the CPU, our algorithm is faster than im2col in most cases.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成为图像和视频处理中最成功的机器学习技术之一。 CNN中计算量最大的部分是卷积层，它将多通道图像与多个内核进行卷积。实现卷积层的常用方法是将图像扩展为列矩阵（im2col），并使用现有的并行通用矩阵乘法（GEMM）库执行多通道多内核（MCMK）卷积。这im2col转换极大地增加了输入矩阵的内存占用，并减少了数据的局部性。在本文中，我们提出了一种基于通用矩阵乘法（GEMM）的MCMK卷积的新方法，但不是在im2col上。我们的算法消除了输入数据复制的需要，从而使我们能够直接在输入图像上应用卷积核。我们已经在CPU处理器和嵌入式ARM处理器上实现了我们算法的几个变体。在CPU上，我们的算法在大多数情况下比im2col快。

##### URL
[https://arxiv.org/abs/1704.04428](https://arxiv.org/abs/1704.04428)

##### PDF
[https://arxiv.org/pdf/1704.04428](https://arxiv.org/pdf/1704.04428)

