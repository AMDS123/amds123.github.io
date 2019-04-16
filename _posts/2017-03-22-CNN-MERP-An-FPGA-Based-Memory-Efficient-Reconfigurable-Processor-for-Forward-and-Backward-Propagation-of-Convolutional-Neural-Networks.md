---
layout: post
title: "CNN-MERP: An FPGA-Based Memory-Efficient Reconfigurable Processor for Forward and Backward Propagation of Convolutional Neural Networks"
date: 2017-03-22 01:31:23
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Xushen Han, Dajiang Zhou, Shihao Wang, Shinji Kimura
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale deep convolutional neural networks (CNNs) are widely used in machine learning applications. While CNNs involve huge complexity, VLSI (ASIC and FPGA) chips that deliver high-density integration of computational resources are regarded as a promising platform for CNN's implementation. At massive parallelism of computational units, however, the external memory bandwidth, which is constrained by the pin count of the VLSI chip, becomes the system bottleneck. Moreover, VLSI solutions are usually regarded as a lack of the flexibility to be reconfigured for the various parameters of CNNs. This paper presents CNN-MERP to address these issues. CNN-MERP incorporates an efficient memory hierarchy that significantly reduces the bandwidth requirements from multiple optimizations including on/off-chip data allocation, data flow optimization and data reuse. The proposed 2-level reconfigurability is utilized to enable fast and efficient reconfiguration, which is based on the control logic and the multiboot feature of FPGA. As a result, an external memory bandwidth requirement of 1.94MB/GFlop is achieved, which is 55% lower than prior arts. Under limited DRAM bandwidth, a system throughput of 1244GFlop/s is achieved at the Vertex UltraScale platform, which is 5.48 times higher than the state-of-the-art FPGA implementations.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.07348](https://arxiv.org/abs/1703.07348)

##### PDF
[https://arxiv.org/pdf/1703.07348](https://arxiv.org/pdf/1703.07348)

