---
layout: post
title: "Scalable Full Flow with Learned Binary Descriptors"
date: 2017-07-20 09:49:29
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Gottfried Munda, Alexander Shekhovtsov, Patrick Knöbelreiter, Thomas Pock
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for large displacement optical flow in which local matching costs are learned by a convolutional neural network (CNN) and a smoothness prior is imposed by a conditional random field (CRF). We tackle the computation- and memory-intensive operations on the 4D cost volume by a min-projection which reduces memory complexity from quadratic to linear and binary descriptors for efficient matching. This enables evaluation of the cost on the fly and allows to perform learning and CRF inference on high resolution images without ever storing the 4D cost volume. To address the problem of learning binary descriptors we propose a new hybrid learning scheme. In contrast to current state of the art approaches for learning binary CNNs we can compute the exact non-zero gradient within our model. We compare several methods for training binary descriptors and show results on public available benchmarks.

##### Abstract (translated by Google)
我们提出了一种大位移光流的方法，其中由卷积神经网络（CNN）学习局部匹配成本，并且通过条件随机场（CRF）施加平滑先验。我们通过最小投影解决4D成本体积上的计算和内存密集型操作，从而将存储器复杂度从二次型降低到线性和二进制描述符以进行高效匹配。这使得能够评估运行成本，并且允许在高分辨率图像上执行学习和CRF推断，而不必存储4D成本体积。为了解决学习二进制描述符的问题，我们提出了一种新的混合学习方案。与当前用于学习二元CNN的现有技术方法相反，我们可以计算模型中的精确的非零梯度。我们比较几种方法来训练二进制描述符，并在公共可用基准上显示结果。

##### URL
[https://arxiv.org/abs/1707.06427](https://arxiv.org/abs/1707.06427)

##### PDF
[https://arxiv.org/pdf/1707.06427](https://arxiv.org/pdf/1707.06427)

