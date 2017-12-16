---
layout: post
title: "Training Bit Fully Convolutional Network for Fast Semantic Segmentation"
date: 2016-12-01 11:56:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Prediction
author: He Wen, Shuchang Zhou, Zhe Liang, Yuxiang Zhang, Dieqiao Feng, Xinyu Zhou, Cong Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional neural networks give accurate, per-pixel prediction for input images and have applications like semantic segmentation. However, a typical FCN usually requires lots of floating point computation and large run-time memory, which effectively limits its usability. We propose a method to train Bit Fully Convolution Network (BFCN), a fully convolutional neural network that has low bit-width weights and activations. Because most of its computation-intensive convolutions are accomplished between low bit-width numbers, a BFCN can be accelerated by an efficient bit-convolution implementation. On CPU, the dot product operation between two bit vectors can be reduced to bitwise operations and popcounts, which can offer much higher throughput than 32-bit multiplications and additions. To validate the effectiveness of BFCN, we conduct experiments on the PASCAL VOC 2012 semantic segmentation task and Cityscapes. Our BFCN with 1-bit weights and 2-bit activations, which runs 7.8x faster on CPU or requires less than 1\% resources on FPGA, can achieve comparable performance as the 32-bit counterpart.

##### Abstract (translated by Google)
完全卷积神经网络为输入图像提供准确的每像素预测，并具有语义分割等应用。然而，典型的FCN通常需要大量的浮点计算和大的运行时间内存，这就有效地限制了其可用性。我们提出了一种训练比特完全卷积网络（BFCN）的方法，该网络是一种具有低位宽度权重和激活的完全卷积神经网络。由于大部分计算密集型卷积是在低位宽度数字之间完成的，因此可以通过有效的位卷积实现来加速BFCN。在CPU上，两个位向量之间的点积运算可以被简化为按位运算和弹出，这可以提供比32位乘法和加法更高的吞吐量。为验证BFCN的有效性，我们对PASCAL VOC 2012语义分割任务和Cityscapes进行了实验。我们的BFCN具有1位权重和2位激活，在CPU上运行速度提高了7.8倍，或者在FPGA上占用的资源少于1％，可以达到与32位相当的性能。

##### URL
[https://arxiv.org/abs/1612.00212](https://arxiv.org/abs/1612.00212)

##### PDF
[https://arxiv.org/pdf/1612.00212](https://arxiv.org/pdf/1612.00212)

