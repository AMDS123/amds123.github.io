---
layout: post
title: "CirCNN: Accelerating and Compressing Deep Neural Networks Using Block-CirculantWeight Matrices"
date: 2017-08-29 04:18:57
categories: arXiv_CV
tags: arXiv_CV Inference
author: Caiwen Ding, Siyu Liao, Yanzhi Wang, Zhe Li, Ning Liu, Youwei Zhuo, Chao Wang, Xuehai Qian, Yu Bai, Geng Yuan, Xiaolong Ma, Yipeng Zhang, Jian Tang, Qinru Qiu, Xue Lin, Bo Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale deep neural networks (DNNs) are both compute and memory intensive. As the size of DNNs continues to grow, it is critical to improve the energy efficiency and performance while maintaining accuracy. For DNNs, the model size is an important factor affecting performance, scalability and energy efficiency. Weight pruning achieves good compression ratios but suffers from three drawbacks: 1) the irregular network structure after pruning; 2) the increased training complexity; and 3) the lack of rigorous guarantee of compression ratio and inference accuracy. To overcome these limitations, this paper proposes CirCNN, a principled approach to represent weights and process neural networks using block-circulant matrices. CirCNN utilizes the Fast Fourier Transform (FFT)-based fast multiplication, simultaneously reducing the computational complexity (both in inference and training) from O(n2) to O(nlogn) and the storage complexity from O(n2) to O(n), with negligible accuracy loss. Compared to other approaches, CirCNN is distinct due to its mathematical rigor: it can converge to the same effectiveness as DNNs without compression. The CirCNN architecture, a universal DNN inference engine that can be implemented on various hardware/software platforms with configurable network architecture. To demonstrate the performance and energy efficiency, we test CirCNN in FPGA, ASIC and embedded processors. Our results show that CirCNN architecture achieves very high energy efficiency and performance with a small hardware footprint. Based on the FPGA implementation and ASIC synthesis results, CirCNN achieves 6-102X energy efficiency improvements compared with the best state-of-the-art results.

##### Abstract (translated by Google)
大规模的深度神经网络（DNN）既是计算量又是内存密集型的。随着DNN尺寸的不断增长，在保持精度的同时提高能效和性能至关重要。对于DNN，模型大小是影响性能，可扩展性和能源效率的重要因素。重量修剪实现了良好的压缩比，但有三个缺点：1）修剪后网络结构不规则; 2）培训复杂性增加; 3）压缩比和推理精度的严格保证不足。为了克服这些限制，本文提出了CirCNN，一种使用块循环矩阵表示权值和处理神经网络的原理方法。 CirCNN利用基于快速傅立叶变换（FFT）的快速乘法，同时降低从O（n2）到O（nlogn）的计算复杂度（包括推理和训练）以及从O（n2）到O（n） ，精度损失可以忽略不计。与其他方法相比，CirCNN由于其数学上的严格性而显着不同：它可以收敛到与没有压缩的DNN相同的有效性。 CirCNN架构是一种通用的DNN推理引擎，可以在具有可配置网络架构的各种硬件/软件平台上实施。为了演示性能和能效，我们在FPGA，ASIC和嵌入式处理器上测试CirCNN。我们的研究结果显示，CirCNN架构以较小的硬件占用空间实现了非常高的能效和性能。基于FPGA实现和ASIC综合结果，CirCNN实现了6-102倍的能效改进，与最佳的最新成果相比。

##### URL
[https://arxiv.org/abs/1708.08917](https://arxiv.org/abs/1708.08917)

##### PDF
[https://arxiv.org/pdf/1708.08917](https://arxiv.org/pdf/1708.08917)

