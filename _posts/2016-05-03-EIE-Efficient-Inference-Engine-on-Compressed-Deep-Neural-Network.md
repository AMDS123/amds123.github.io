---
layout: post
title: "EIE: Efficient Inference Engine on Compressed Deep Neural Network"
date: 2016-05-03 04:27:02
categories: arXiv_CV
tags: arXiv_CV Sparse Inference
author: Song Han, Xingyu Liu, Huizi Mao, Jing Pu, Ardavan Pedram, Mark A. Horowitz, William J. Dally
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art deep neural networks (DNNs) have hundreds of millions of connections and are both computationally and memory intensive, making them difficult to deploy on embedded systems with limited hardware resources and power budgets. While custom hardware helps the computation, fetching weights from DRAM is two orders of magnitude more expensive than ALU operations, and dominates the required power. Previously proposed 'Deep Compression' makes it possible to fit large DNNs (AlexNet and VGGNet) fully in on-chip SRAM. This compression is achieved by pruning the redundant connections and having multiple connections share the same weight. We propose an energy efficient inference engine (EIE) that performs inference on this compressed network model and accelerates the resulting sparse matrix-vector multiplication with weight sharing. Going from DRAM to SRAM gives EIE 120x energy saving; Exploiting sparsity saves 10x; Weight sharing gives 8x; Skipping zero activations from ReLU saves another 3x. Evaluated on nine DNN benchmarks, EIE is 189x and 13x faster when compared to CPU and GPU implementations of the same DNN without compression. EIE has a processing power of 102GOPS/s working directly on a compressed network, corresponding to 3TOPS/s on an uncompressed network, and processes FC layers of AlexNet at 1.88x10^4 frames/sec with a power dissipation of only 600mW. It is 24,000x and 3,400x more energy efficient than a CPU and GPU respectively. Compared with DaDianNao, EIE has 2.9x, 19x and 3x better throughput, energy efficiency and area efficiency.

##### Abstract (translated by Google)
最先进的深度神经网络（DNN）具有数以亿计的连接，并且在计算上和内存上都很密集，使得它们难以在具有有限的硬件资源和功率预算的嵌入式系统上部署。虽然定制硬件有助于计算，但从DRAM获取权重比ALU操作贵两个数量级，并且支配所需功率。之前提出的“深度压缩”可以使大型DNN（AlexNet和VGGNet）完全适用于片上SRAM。这种压缩是通过修剪冗余连接并使多个连接共享相同的权重来实现的。我们提出了一个能量有效推理引擎（EIE），对这个压缩的网络模型进行推理，并加速所产生的稀疏矩阵向量乘以权重共享。从DRAM到SRAM让EIE 120x节能;利用稀疏节省10倍;重量分享给8倍;从ReLU跳过零激活保存另一个3倍。与9个DNN基准评估相比，相比同一个DNN的CPU和GPU实现，EIE的速度要快189倍和13倍。 EIE具有102GOPS / s的处理能力，直接在压缩网络上工作，对应于未压缩网络上的3TOPS / s，以1.88x10 ^ 4帧/秒的速率处理AlexNet的FC层，功耗仅为600mW。比CPU和GPU分别节能24000倍和3400倍。与大电脑相比，EIE的吞吐量，能源效率和面积效率分别提高了2.9倍，19倍和3倍。

##### URL
[https://arxiv.org/abs/1602.01528](https://arxiv.org/abs/1602.01528)

##### PDF
[https://arxiv.org/pdf/1602.01528](https://arxiv.org/pdf/1602.01528)

