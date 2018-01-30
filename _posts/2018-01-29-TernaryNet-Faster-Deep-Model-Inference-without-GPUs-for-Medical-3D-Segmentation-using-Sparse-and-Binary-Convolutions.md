---
layout: post
title: "TernaryNet: Faster Deep Model Inference without GPUs for Medical 3D Segmentation using Sparse and Binary Convolutions"
date: 2018-01-29 11:13:43
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Inference Deep_Learning Prediction
author: Mattias P. Heinrich, Max Blendowski, Ozan Oktay
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (DCNN) are currently ubiquitous in medical imaging. While their versatility and high quality results for common image analysis tasks including segmentation, localisation and prediction is astonishing, the large representational power comes at the cost of highly demanding computational effort. This limits their practical applications for image guided interventions and diagnostic (point-of-care) support using mobile devices without graphics processing units (GPU). We propose a new scheme that approximates both trainable weights and neural activations in deep networks by ternary values and tackles the open question of backpropagation when dealing with non-differentiable functions. Our solution enables the removal of the expensive floating-point matrix multiplications throughout any convolutional neural network and replaces them by energy and time preserving binary operators and population counts. Our approach, which is demonstrated using a fully-convolutional network (FCN) for CT pancreas segmentation leads to more than 10-fold reduced memory requirements and we provide a concept for sub-second inference without GPUs. Our ternary approximation obtains high accuracies (without any post-processing) with a Dice overlap of 71.0% that are statistically equivalent to using networks with high-precision weights and activations. We further demonstrate the significant improvements reached in comparison to binary quantisation and without our proposed ternary hyperbolic tangent continuation. We present a key enabling technique for highly efficient DCNN inference without GPUs that will help to bring the advances of deep learning to practical clinical applications. It has also great promise for improving accuracies in large-scale medical data retrieval.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）目前在医疗成像中无处不在。尽管对于常见的图像分析任务（包括分割，定位和预测）而言，其多功能性和高质量结果令人惊讶，但其代表性的强大代价是要求极高的计算成本。这限制了其使用没有图形处理单元（GPU）的移动设备的图像引导干预和诊断（即时护理）支持的实际应用。我们提出了一种新的方案，通过三元值逼近深度网络中的可训练权重和神经激活，并在处理不可微函数时解决反向传播的开放问题。我们的解决方案能够消除整个卷积神经网络中昂贵的浮点矩阵乘法，并通过保留二元运算符和总体数量的能量和时间来替代它们。我们的方法，使用完全卷积网络（FCN）进行CT胰腺分割，可以减少10倍以上的内存需求，我们提供了一个无GPU的亚秒级推理概念。我们的三元逼近获得了高精度（没有任何后处理），其中71.0％的骰子重叠在统计上等同于使用具有高精确度权重和激活的网络。我们进一步证明了与二进制量化相比显着的改进，并且没有我们提出的三元双曲线正切延续。我们提出了一个关键的使能技术，无需GPU的高效DCNN推理，将有助于将深度学习的进展带到实际的临床应用。对于提高大规模医疗数据检索的准确性也有很大的前景。

##### URL
[http://arxiv.org/abs/1801.09449](http://arxiv.org/abs/1801.09449)

##### PDF
[http://arxiv.org/pdf/1801.09449](http://arxiv.org/pdf/1801.09449)

