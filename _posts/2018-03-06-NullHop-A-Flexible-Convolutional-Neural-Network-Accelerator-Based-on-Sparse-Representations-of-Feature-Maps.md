---
layout: post
title: "NullHop: A Flexible Convolutional Neural Network Accelerator Based on Sparse Representations of Feature Maps"
date: 2018-03-06 10:05:33
categories: arXiv_CV
tags: arXiv_CV Sparse Face CNN Inference
author: Alessandro Aimar, Hesham Mostafa, Enrico Calabrese, Antonio Rios-Navarro, Ricardo Tapiador-Morales, Iulia-Alexandra Lungu, Moritz B. Milde, Federico Corradi, Alejandro Linares-Barranco, Shih-Chii Liu, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) have become the dominant neural network architecture for solving many state-of-the-art (SOA) visual processing tasks. Even though Graphical Processing Units (GPUs) are most often used in training and deploying CNNs, their power efficiency is less than 10 GOp/s/W for single-frame runtime inference. We propose a flexible and efficient CNN accelerator architecture called NullHop that implements SOA CNNs useful for low-power and low-latency application scenarios. NullHop exploits the sparsity of neuron activations in CNNs to accelerate the computation and reduce memory requirements. The flexible architecture allows high utilization of available computing resources across kernel sizes ranging from 1x1 to 7x7. NullHop can process up to 128 input and 128 output feature maps per layer in a single pass. We implemented the proposed architecture on a Xilinx Zynq FPGA platform and present results showing how our implementation reduces external memory transfers and compute time in five different CNNs ranging from small ones up to the widely known large VGG16 and VGG19 CNNs. Post-synthesis simulations using Mentor Modelsim in a 28nm process with a clock frequency of 500 MHz show that the VGG19 network achieves over 450 GOp/s. By exploiting sparsity, NullHop achieves an efficiency of 368%, maintains over 98% utilization of the MAC units, and achieves a power efficiency of over 3TOp/s/W in a core area of 6.3mm$^2$. As further proof of NullHop's usability, we interfaced its FPGA implementation with a neuromorphic event camera for real time interactive demonstrations.

##### Abstract (translated by Google)
卷积神经网络（CNN）已成为解决许多最先进的（SOA）视觉处理任务的主导神经网络体系结构。尽管图形处理单元（GPU）最常用于培训和部署CNN，但对于单帧运行时推理，其功率效率低于10 GOp / s / W。我们提出了一种名为NullHop的灵活且高效的CNN加速器体系结构，实现了对低功耗和低延迟应用场景有用的SOA CNN。 NullHop利用CNN中神经元激活的稀疏性来加速计算并降低内存需求。灵活的架构允许在1x1到7x7范围内的内核大小中高度利用可用的计算资源。 NullHop可以一次处理多达128个输入和128个输出特征图。我们实施了建议的架构赛灵思FPGA ZYNQ平台，目前的结果显示我们实现如何减少外部存储器传输，并在五个不同的细胞神经网络的计算时间从小型的人了广为人知的大VGG16和VGG19细胞神经网络上。使用Mentor Modelsim进行28nm工艺，时钟频率为500 MHz的后综合仿真表明，VGG19网络可以达到450 GOp / s以上。通过利用稀疏性，NullHop达到368％的效率，保持对MAC单元98％的利用率，并且在6.3毫米$ ^ 2 $芯面积达到超过3TOp / S / W的功率效率。作为NullHop可用性的进一步证明，我们将其FPGA实现与神经形态事件相机连接起来，以进行实时交互式演示。

##### URL
[http://arxiv.org/abs/1706.01406](http://arxiv.org/abs/1706.01406)

##### PDF
[http://arxiv.org/pdf/1706.01406](http://arxiv.org/pdf/1706.01406)

