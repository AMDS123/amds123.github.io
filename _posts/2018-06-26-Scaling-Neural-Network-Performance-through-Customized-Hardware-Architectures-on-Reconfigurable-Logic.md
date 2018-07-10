---
layout: post
title: "Scaling Neural Network Performance through Customized Hardware Architectures on Reconfigurable Logic"
date: 2018-06-26 14:39:44
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction
author: Michaela Blott, Thomas B. Preusser, Nicholas Fraser, Giulio Gambardella, Kenneth OBrien, Yaman Umuroglu, Miriam Leeser
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks have dramatically improved in recent years, surpassing human accuracy on certain problems and performance exceeding that of traditional computer vision algorithms. While the compute pattern in itself is relatively simple, significant compute and memory challenges remain as CNNs may contain millions of floating-point parameters and require billions of floating-point operations to process a single image. These computational requirements, combined with storage footprints that exceed typical cache sizes, pose a significant performance and power challenge for modern compute architectures. One of the promising opportunities to scale performance and power efficiency is leveraging reduced precision representations for all activations and weights as this allows to scale compute capabilities, reduce weight and feature map buffering requirements as well as energy consumption. While a small reduction in accuracy is encountered, these Quantized Neural Networks have been shown to achieve state-of-the-art accuracy on standard benchmark datasets, such as MNIST, CIFAR-10, SVHN and even ImageNet, and thus provide highly attractive design trade-offs. Current research has focused mainly on the implementation of extreme variants with full binarization of weights and or activations, as well typically smaller input images. Within this paper, we investigate the scalability of dataflow architectures with respect to supporting various precisions for both weights and activations, larger image dimensions, and increasing numbers of feature map channels. Key contributions are a formalized approach to understanding the scalability of the existing hardware architecture with cost models and a performance prediction as a function of the target device size. We provide validating experimental results for an ImageNet classification on a server-class platform, namely the AWS F1 node.

##### Abstract (translated by Google)
卷积神经网络近年来得到了极大的改进，超越了人类对某些问题的准确性和性能，超过了传统的计算机视觉算法。虽然计算模式本身相对简单，但仍然存在重大的计算和内存挑战，因为CNN可能包含数百万个浮点参数，并且需要数十亿个浮点运算来处理单个映像。这些计算要求与超出典型高速缓存大小的存储占用空间相结合，为现代计算架构带来了显着的性能和功耗挑战。扩展性能和功率效率的一个有希望的机会是利用所有激活和权重的精度降低表示，因为这样可以扩展计算能力，减轻重量和功能图缓冲要求以及能耗。虽然遇到了精确度的小幅下降，但这些量化神经网络已被证明可以在标准基准数据集（如MNIST，CIFAR-10，SVHN甚至ImageNet）上实现最先进的精度，从而提供极具吸引力的设计权衡。目前的研究主要集中在通过权重和/或激活的完全二值化的极端变体的实现，以及通常较小的输入图像。在本文中，我们研究了数据流架构的可扩展性，以支持权重和激活的各种精度，更大的图像尺寸以及越来越多的特征映射通道。主要贡献是通过成本模型和作为目标设备大小函数的性能预测来理解现有硬件架构的可扩展性的形式化方法。我们在服务器级平台（即AWS F1节点）上为ImageNet分类提供验证实验结果。

##### URL
[http://arxiv.org/abs/1807.03123](http://arxiv.org/abs/1807.03123)

##### PDF
[http://arxiv.org/pdf/1807.03123](http://arxiv.org/pdf/1807.03123)

