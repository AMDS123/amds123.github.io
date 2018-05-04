---
layout: post
title: "Ultra Power-Efficient CNN Domain Specific Accelerator with 9.3TOPS/Watt for Mobile and Embedded Applications"
date: 2018-04-30 17:36:14
categories: arXiv_AI
tags: arXiv_AI CNN
author: Baohua Sun, Lin Yang, Patrick Dong, Wenhan Zhang, Jason Dong, Charles Young
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision performances have been significantly improved in recent years by Convolutional Neural Networks(CNN). Currently, applications using CNN algorithms are deployed mainly on general purpose hardwares, such as CPUs, GPUs or FPGAs. However, power consumption, speed, accuracy, memory footprint, and die size should all be taken into consideration for mobile and embedded applications. Domain Specific Architecture (DSA) for CNN is the efficient and practical solution for CNN deployment and implementation. We designed and produced a 28nm Two-Dimensional CNN-DSA accelerator with an ultra power-efficient performance of 9.3TOPS/Watt and with all processing done in the internal memory instead of outside DRAM. It classifies 224x224 RGB image inputs at more than 140fps with peak power consumption at less than 300mW and an accuracy comparable to the VGG benchmark. The CNN-DSA accelerator is reconfigurable to support CNN model coefficients of various layer sizes and layer types, including convolution, depth-wise convolution, short-cut connections, max pooling, and ReLU. Furthermore, in order to better support real-world deployment for various application scenarios, especially with low-end mobile and embedded platforms and MCUs (Microcontroller Units), we also designed algorithms to fully utilize the CNN-DSA accelerator efficiently by reducing the dependency on external accelerator computation resources, including implementation of Fully-Connected (FC) layers within the accelerator and compression of extracted features from the CNN-DSA accelerator. Live demos with our CNN-DSA accelerator on mobile and embedded systems show its capabilities to be widely and practically applied in the real world.

##### Abstract (translated by Google)
卷积神经网络（CNN）近年来显着提高了计算机视觉性能。目前，使用CNN算法的应用程序主要部署在通用硬件上，如CPU，GPU或FPGA。但是，移动和嵌入式应用都应考虑功耗，速度，精度，内存占用空间和芯片尺寸。针对CNN的域特定体系结构（DSA）是CNN部署和实施的高效实用解决方案。我们设计并制造了28nm二维CNN-DSA加速器，具有9.3TOPS / Watt的超高功效性能，并且所有处理均在内部存储器中完成，而不是在外部DRAM中完成。它将224x224 RGB图像输入分类为超过140fps，峰值功耗低于300mW，准确度与VGG基准相当。 CNN-DSA加速器可重新配置为支持不同层大小和层类型的CNN模型系数，包括卷积，深度卷积，快捷连接，最大池化和ReLU。此外，为了更好地支持各种应用场景的实际部署，特别是低端移动和嵌入式平台以及MCU（微控制器单元），我们还设计了算法，以充分利用CNN-DSA加速器，从而减少对外部加速器计算资源，包括在加速器内实现完全连接（FC）层以及从CNN-DSA加速器压缩提取的特征。我们在移动和嵌入式系统上使用CNN-DSA加速器的实时演示显示了其在现实世界中广泛和实际应用的能力。

##### URL
[https://arxiv.org/abs/1805.00361](https://arxiv.org/abs/1805.00361)

##### PDF
[https://arxiv.org/pdf/1805.00361](https://arxiv.org/pdf/1805.00361)

