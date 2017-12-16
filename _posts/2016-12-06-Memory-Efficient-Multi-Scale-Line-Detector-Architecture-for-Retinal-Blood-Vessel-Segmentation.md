---
layout: post
title: "Memory Efficient Multi-Scale Line Detector Architecture for Retinal Blood Vessel Segmentation"
date: 2016-12-06 19:06:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Hamza Bendaoudi, Farida Cheriet, J. M. Pierre Langlois
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a memory efficient architecture that implements the Multi-Scale Line Detector (MSLD) algorithm for real-time retinal blood vessel detection in fundus images on a Zynq FPGA. This implementation benefits from the FPGA parallelism to drastically reduce the memory requirements of the MSLD from two images to a few values. The architecture is optimized in terms of resource utilization by reusing the computations and optimizing the bit-width. The throughput is increased by designing fully pipelined functional units. The architecture is capable of achieving a comparable accuracy to its software implementation but 70x faster for low resolution images. For high resolution images, it achieves an acceleration by a factor of 323x.

##### Abstract (translated by Google)
本文提出了一种内存有效的架构，实现了在Zynq FPGA的眼底图像中进行实时视网膜血管检测的多尺度线检测器（MSLD）算法。这种实现从FPGA并行性中受益，从而将MSLD的存储器需求从两个图像大幅降低到几个值。通过重新使用计算并优化比特宽度，对架构进行了资源利用率的优化。通过设计完全流水线的功能单元来提高吞吐量。该架构能够实现与其软件实现相当的准确度，但对于低分辨率图像要快70倍。对于高分辨率的图像，它实现了323倍的加速。

##### URL
[https://arxiv.org/abs/1612.09524](https://arxiv.org/abs/1612.09524)

##### PDF
[https://arxiv.org/pdf/1612.09524](https://arxiv.org/pdf/1612.09524)

