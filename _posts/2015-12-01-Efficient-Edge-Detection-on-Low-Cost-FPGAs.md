---
layout: post
title: "Efficient Edge Detection on Low-Cost FPGAs"
date: 2015-12-01 22:32:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Jamie Schiel, Andrew Bainbridge-Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Improving the efficiency of edge detection in embedded applications, such as UAV control, is critical for reducing system cost and power dissipation. Field programmable gate arrays (FPGA) are a good platform for making improvements because of their specialised internal structure. However, current FPGA edge detectors do not exploit this structure well. A new edge detection architecture is proposed that is better optimised for FPGAs. The basis of the architecture is the Sobel edge kernels that are shown to be the most suitable because of their separability and absence of multiplications. Edge intensities are calculated with a new 4:2 compressor that consists of two custom-designed 3:2 compressors. Addition speed is increased by breaking carry propagation chains with look-ahead logic. Testing of the design showed it gives a 28% increase in speed and 4.4% reduction in area over previous equivalent designs, which demonstrated that it will lower the cost of edge detection systems, dissipate less power and still maintain high-speed control.

##### Abstract (translated by Google)
提高嵌入式应用（如无人机控制）中边缘检测的效率对于降低系统成本和功耗至关重要。现场可编程门阵列（FPGA）由于其专门的内部结构而成为改进的良好平台。但是，目前的FPGA边缘检测器并没有很好地利用这种结构。提出了一种新的边缘检测架构，可以更好地优化FPGA。该体系结构的基础是Sobel边缘内核，由于其可分离性和不存在乘法性，因此被证明是最合适的。边缘强度是用一个新的4：2压缩机计算的，它由两个定制的3：2压缩机组成。用先行逻辑打破进位传播链，提高了加速度。设计测试表明，与以前的等效设计相比，它的速度提高了28％，面积减少了4.4％，这表明它将降低边缘检测系统的成本，耗散更少的功率，并且仍然保持高速控制。

##### URL
[https://arxiv.org/abs/1512.00504](https://arxiv.org/abs/1512.00504)

##### PDF
[https://arxiv.org/pdf/1512.00504](https://arxiv.org/pdf/1512.00504)

