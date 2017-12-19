---
layout: post
title: "Automated flow for compressing convolution neural networks for efficient edge-computation with FPGA"
date: 2017-12-18 07:02:07
categories: arXiv_AI
tags: arXiv_AI Object_Detection CNN Optimization Inference Detection
author: Farhan Shafiq, Takato Yamada, Antonio T. Vilchez, Sakyasingha Dasgupta
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNN) based solutions are the current state- of-the-art for computer vision tasks. Due to the large size of these models, they are typically run on clusters of CPUs or GPUs. However, power requirements and cost budgets can be a major hindrance in adoption of CNN for IoT applications. Recent research highlights that CNN contain significant redundancy in their structure and can be quantized to lower bit-width parameters and activations, while maintaining acceptable accuracy. Low bit-width and especially single bit-width (binary) CNN are particularly suitable for mobile applications based on FPGA implementation, due to the bitwise logic operations involved in binarized CNN. Moreover, the transition to lower bit-widths opens new avenues for performance optimizations and model improvement. In this paper, we present an automatic flow from trained TensorFlow models to FPGA system on chip implementation of binarized CNN. This flow involves quantization of model parameters and activations, generation of network and model in embedded-C, followed by automatic generation of the FPGA accelerator for binary convolutions. The automated flow is demonstrated through implementation of binarized "YOLOV2" on the low cost, low power Cyclone- V FPGA device. Experiments on object detection using binarized YOLOV2 demonstrate significant performance benefit in terms of model size and inference speed on FPGA as compared to CPU and mobile CPU platforms. Furthermore, the entire automated flow from trained models to FPGA synthesis can be completed within one hour.

##### Abstract (translated by Google)
基于深度卷积神经网络（CNN）的解决方案是目前计算机视觉任务的最新技术。由于这些模型的大尺寸，它们通常运行在CPU或GPU集群上。然而，电力需求和成本预算可能成为采用CNN进行物联网应用的主要障碍。最近的研究表明，CNN在其结构中包含重要的冗余，可以量化为更低的位宽参数和激活，同时保持可接受的精度。由于二进制CNN中涉及的按位逻辑操作，所以低位宽和尤其是单位宽（二进制）CNN特别适合基于FPGA实现的移动应用。而且，向较低位宽度的过渡为性能优化和模型改进开辟了新的途径。在本文中，我们提出了一个从经过训练的TensorFlow模型到二进制CNN的片上实现的自动流程。该流程涉及模型参数和激活的量化，嵌入式C中网络和模型的生成，随后自动生成用于二进制卷积的FPGA加速器。通过在低成本，低功耗的Cyclone-V FPGA器件上实现二进制“YOLOV2”，演示了自动化流程。使用二值化YOLOV2进行物体检测的实验，与CPU和移动CPU平台相比，在FPGA的模型尺寸和推理速度方面表现出显着的性能优势。此外，从训练模型到FPGA综合的整个自动化流程可以在一个小时内完成。

##### URL
[http://arxiv.org/abs/1712.06272](http://arxiv.org/abs/1712.06272)

##### PDF
[http://arxiv.org/pdf/1712.06272](http://arxiv.org/pdf/1712.06272)

