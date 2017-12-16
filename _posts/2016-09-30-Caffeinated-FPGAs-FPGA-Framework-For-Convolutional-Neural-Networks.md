---
layout: post
title: "Caffeinated FPGAs: FPGA Framework For Convolutional Neural Networks"
date: 2016-09-30 11:13:21
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Roberto DiCecco, Griffin Lacey, Jasmina Vasiljevic, Paul Chow, Graham Taylor, Shawki Areibi
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have gained significant traction in the field of machine learning, particularly due to their high accuracy in visual recognition. Recent works have pushed the performance of GPU implementations of CNNs to significantly improve their classification and training times. With these improvements, many frameworks have become available for implementing CNNs on both CPUs and GPUs, with no support for FPGA implementations. In this work we present a modified version of the popular CNN framework Caffe, with FPGA support. This allows for classification using CNN models and specialized FPGA implementations with the flexibility of reprogramming the device when necessary, seamless memory transactions between host and device, simple-to-use test benches, and the ability to create pipelined layer implementations. To validate the framework, we use the Xilinx SDAccel environment to implement an FPGA-based Winograd convolution engine and show that the FPGA layer can be used alongside other layers running on a host processor to run several popular CNNs (AlexNet, GoogleNet, VGG A, Overfeat). The results show that our framework achieves 50 GFLOPS across 3x3 convolutions in the benchmarks. This is achieved within a practical framework, which will aid in future development of FPGA-based CNNs.

##### Abstract (translated by Google)
卷积神经网络（CNN）在机器学习领域获得了巨大的推动，特别是由于其在视觉识别方面的高精度。最近的作品推动了CNN的GPU实现的性能，以显着改善它们的分类和训练时间。随着这些改进，许多框架已经可用于在CPU和GPU上实现CNN，而不支持FPGA实现。在这项工作中，我们提出了一个流行的CNN框架Caffe的修改版本，并支持FPGA。这允许使用CNN模型和专用FPGA实现进行分类，在必要时可以灵活地对设备进行重新编程，主机和设备之间的无缝存储器事务，简单易用的测试平台以及创建流水线层实现的能力。为验证框架，我们使用Xilinx SDAccel环境来实现基于FPGA的Winograd卷积引擎，并显示FPGA层可以与主处理器上运行的其他层一起使用，以运行几个流行的CNN（AlexNet，GoogleNet，VGG A， Overfeat）。结果显示，我们的框架在基准测试中的3x3卷积中达到了50 GFLOPS。这是在一个实际的框架内实现的，这将有助于今后开发基于FPGA的CNN。

##### URL
[https://arxiv.org/abs/1609.09671](https://arxiv.org/abs/1609.09671)

##### PDF
[https://arxiv.org/pdf/1609.09671](https://arxiv.org/pdf/1609.09671)

