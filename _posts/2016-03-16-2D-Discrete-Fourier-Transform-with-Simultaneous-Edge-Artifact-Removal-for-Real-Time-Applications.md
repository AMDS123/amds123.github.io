---
layout: post
title: "2D Discrete Fourier Transform with Simultaneous Edge Artifact Removal for Real-Time Applications"
date: 2016-03-16 15:52:13
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Faisal Mahmood, Märt Toots, Lars-Göran Öfverstedt, Ulf Skoglund
mathjax: true
---

* content
{:toc}

##### Abstract
Two-Dimensional (2D) Discrete Fourier Transform (DFT) is a basic and computationally intensive algorithm, with a vast variety of applications. 2D images are, in general, non-periodic, but are assumed to be periodic while calculating their DFTs. This leads to cross-shaped artifacts in the frequency domain due to spectral leakage. These artifacts can have critical consequences if the DFTs are being used for further processing. In this paper we present a novel FPGA-based design to calculate high-throughput 2D DFTs with simultaneous edge artifact removal. Standard approaches for removing these artifacts using apodization functions or mirroring, either involve removing critical frequencies or a surge in computation by increasing image size. We use a periodic-plus-smooth decomposition based artifact removal algorithm optimized for FPGA implementation, while still achieving real-time ($\ge$23 frames per second) performance for a 512$\times$512 size image stream. Our optimization approach leads to a significant decrease in external memory utilization thereby avoiding memory conflicts and simplifies the design. We have tested our design on a PXIe based Xilinx Kintex 7 FPGA system communicating with a host PC which gives us the advantage to further expand the design for industrial applications.

##### Abstract (translated by Google)
二维（2D）离散傅里叶变换（DFT）是一种基本的计算密集型算法，具有广泛的应用。二维图像通常是非周期性的，但在计算其DFT时被假定为周期性的。这会由于频谱泄漏而导致频域中的十字形伪像。如果DFT被用于进一步处理，这些工件可能会产生严重后果。在本文中，我们提出了一种新颖的基于FPGA的设计来计算高吞吐量2D DFT同时边缘伪像去除。使用切趾函数或镜像消除这些伪影的标准方法要么通过增加图像大小来消除临界频率或计算浪涌。我们使用基于周期加光滑分解的伪像去除算法，针对FPGA实现进行了优化，同时仍然实现512美元的512倍大小的图像流的实时性（每秒23帧）。我们的优化方法导致外部存储器利用率显着下降，从而避免存储器冲突并简化设计。我们在基于PXIe的Xilinx Kintex 7 FPGA系统上测试了我们的设计，与主机PC进行通信，这为我们进一步扩展工业应用设计提供了便利。

##### URL
[https://arxiv.org/abs/1603.05154](https://arxiv.org/abs/1603.05154)

##### PDF
[https://arxiv.org/pdf/1603.05154](https://arxiv.org/pdf/1603.05154)

