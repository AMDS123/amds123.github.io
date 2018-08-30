---
layout: post
title: "FPGA Implementation of Convolutional Neural Networks with Fixed-Point Calculations"
date: 2018-08-29 17:51:39
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Recognition
author: Roman A. Solovyev, Alexandr A. Kalinin, Alexander G. Kustov, Dmitry V. Telpukhov, Vladimir S. Ruhlov
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network-based methods for image processing are becoming widely used in practical applications. Modern neural networks are computationally expensive and require specialized hardware, such as graphics processing units. Since such hardware is not always available in real life applications, there is a compelling need for the design of neural networks for mobile devices. Mobile neural networks typically have reduced number of parameters and require a relatively small number of arithmetic operations. However, they usually still are executed at the software level and use floating-point calculations. The use of mobile networks without further optimization may not provide sufficient performance when high processing speed is required, for example, in real-time video processing (30 frames per second). In this study, we suggest optimizations to speed up computations in order to efficiently use already trained neural networks on a mobile device. Specifically, we propose an approach for speeding up neural networks by moving computation from software to hardware and by using fixed-point calculations instead of floating-point. We propose a number of methods for neural network architecture design to improve the performance with fixed-point calculations. We also show an example of how existing datasets can be modified and adapted for the recognition task in hand. Finally, we present the design and the implementation of a floating-point gate array-based device to solve the practical problem of real-time handwritten digit classification from mobile camera video feed.

##### Abstract (translated by Google)
基于神经网络的图像处理方法正在实际应用中得到广泛应用。现代神经网络在计算上很昂贵并且需要专用硬件，例如图形处理单元。由于这种硬件在现实生活中并不总是可用，因此迫切需要为移动设备设计神经网络。移动神经网络通常具有减少的参数数量并且需要相对少量的算术运算。但是，它们通常仍然在软件级别执行并使用浮点计算。没有进一步优化的移动网络的使用可能无法在需要高处理速度时提供足够的性能，例如，在实时视频处理（每秒30帧）中。在本研究中，我们建议优化以加速计算，以便在移动设备上有效地使用已经训练过的神经网络。具体来说，我们提出了一种通过将计算从软件转移到硬件并使用定点计算而不是浮点来加速神经网络的方法。我们提出了许多神经网络架构设计方法，以通过定点计算提高性能。我们还展示了如何修改和调整现有数据集以用于手头的识别任务的示例。最后，我们介绍了基于浮点门阵列的设备的设计和实现，以解决移动摄像机视频输入中实时手写数字分类的实际问题。

##### URL
[http://arxiv.org/abs/1808.09945](http://arxiv.org/abs/1808.09945)

##### PDF
[http://arxiv.org/pdf/1808.09945](http://arxiv.org/pdf/1808.09945)

