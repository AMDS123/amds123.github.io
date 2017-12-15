---
layout: post
title: "Efficient Convolutional Neural Networks for Pixelwise Classification on Heterogeneous Hardware Systems"
date: 2015-09-11 01:20:46
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Prediction
author: Fabian Tschopp
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents and analyzes three convolutional neural network (CNN) models for efficient pixelwise classification of images. When using convolutional neural networks to classify single pixels in patches of a whole image, a lot of redundant computations are carried out when using sliding window networks. This set of new architectures solve this issue by either removing redundant computations or using fully convolutional architectures that inherently predict many pixels at once. The implementations of the three models are accessible through a new utility on top of the Caffe library. The utility provides support for a wide range of image input and output formats, pre-processing parameters and methods to equalize the label histogram during training. The Caffe library has been extended by new layers and a new backend for availability on a wider range of hardware such as CPUs and GPUs through OpenCL. On AMD GPUs, speedups of $54\times$ (SK-Net), $437\times$ (U-Net) and $320\times$ (USK-Net) have been observed, taking the SK equivalent SW (sliding window) network as the baseline. The label throughput is up to one megapixel per second. The analyzed neural networks have distinctive characteristics that apply during training or processing, and not every data set is suitable to every architecture. The quality of the predictions is assessed on two neural tissue data sets, of which one is the ISBI 2012 challenge data set. Two different loss functions, Malis loss and Softmax loss, were used during training. The whole pipeline, consisting of models, interface and modified Caffe library, is available as Open Source software under the working title Project Greentea.

##### Abstract (translated by Google)
这项工作提出和分析三个卷积神经网络（CNN）模型的图像有效像素分类。当使用卷积神经网络对整幅图像中的单个像素进行分类时，在使用滑动窗口网络时会执行大量的冗余计算。这套新的体系结构通过消除冗余计算或使用固有地预测许多像素的完全卷积体系结构来解决此问题。这三个模型的实现可以通过Caffe库之上的一个新实用程序来访问。该实用程序支持广泛的图像输入和输出格式，预处理参数和方法来均衡训练期间的标签直方图。 Caffe库已经扩展了新的层次，并通过OpenCL在更广泛的硬件（如CPU和GPU）上提供了一个新的后端。在AMD的GPU上，已经观察到了$ 54 / times $（SK-Net），$ 437 \ times $（U-Net）和$ 320 \ times $（USK-Net）的加速，基线。标签吞吐量高达每秒一百万像素。分析的神经网络在训练或处理过程中具有独特的特征，并不是每个数据集都适合于每个体系结构。预测的质量在两个神经组织数据集上进行评估，其中一个是ISBI 2012挑战数据集。训练期间使用了两种不同的损失函数，Malis损失和Softmax损失。整个管道，包括模型，接口和修改的Caffe库，可以作为开源软件在Project Greentea项目下提供。

##### URL
[https://arxiv.org/abs/1509.03371](https://arxiv.org/abs/1509.03371)

##### PDF
[https://arxiv.org/pdf/1509.03371](https://arxiv.org/pdf/1509.03371)

