---
layout: post
title: "RAPIDNN: In-Memory Deep Neural Network Acceleration Framework"
date: 2018-06-15 03:07:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Speech_Recognition Recognition
author: Mohsen Imani, Mohammad Samragh, Yeseong Kim, Saransh Gupta, Farinaz Koushanfar, Tajana Rosing
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNN) have demonstrated effectiveness for various applications such as image processing, video segmentation, and speech recognition. Running state-of-the-art DNNs on current systems mostly relies on either general purpose processors, ASIC designs, or FPGA accelerators, all of which suffer from data movements due to the limited on chip memory and data transfer bandwidth. In this work, we propose a novel framework, called RAPIDNN, which processes all DNN operations within the memory to minimize the cost of data movement. To enable in-memory processing, RAPIDNN reinterprets a DNN model and maps it into a specialized accelerator, which is designed using non-volatile memory blocks that model four fundamental DNN operations, i.e., multiplication, addition, activation functions, and pooling. The framework extracts representative operands of a DNN model, e.g., weights and input values, using clustering methods to optimize the model for in-memory processing. Then, it maps the extracted operands and their precomputed results into the accelerator memory blocks. At runtime, the accelerator identifies computation results based on efficient in-memory search capability which also provides tunability of approximation to further improve computation efficiency. Our evaluation shows that RAPIDNN achieves 382.6x, 13.4x energy improvement and 211.5x, 5.6x performance speedup as compared to GPU-based DNN and the state-of-the-art DNN accelerator, while ensuring less than 0.3% of quality loss.

##### Abstract (translated by Google)
深度神经网络（DNN）已经证明了各种应用的有效性，例如图像处理，视频分割和语音识别。在当前系统上运行最先进的DNN主要依靠通用处理器，ASIC设计或FPGA加速器，所有这些都由于有限的片上存储器和数据传输带宽而受到数据移动的困扰。在这项工作中，我们提出了一个新的框架，称为RAPIDNN，它处理内存中的所有DNN操作，以最小化数据移动的成本。为了启用内存中的处理，RAPIDNN重新解释DNN模型并将其映射到专用加速器中，该加速器使用非易失性内存块设计，该模块对四种基本DNN操作（即乘法，加法，激活函数和池）建模。该框架使用聚类方法来提取DNN模型的代表性操作数，例如权重和输入值，以优化用于存储器内处理的模型。然后，它将提取的操作数及其预先计算的结果映射到加速器内存块中。在运行时，加速器基于高效的内存中搜索能力来识别计算结果，其还提供近似的可调性以进一步提高计算效率。我们的评估显示，与基于GPU的DNN和最先进的DNN加速器相比，RAPIDNN的能耗提升382.6倍，能耗提升13.4倍，性能提升211.5倍，性能提升5.6倍，同时确保质量损失低于0.3％。

##### URL
[https://arxiv.org/abs/1806.05794](https://arxiv.org/abs/1806.05794)

##### PDF
[https://arxiv.org/pdf/1806.05794](https://arxiv.org/pdf/1806.05794)

