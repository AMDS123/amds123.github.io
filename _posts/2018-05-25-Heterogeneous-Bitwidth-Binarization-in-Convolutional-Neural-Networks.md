---
layout: post
title: "Heterogeneous Bitwidth Binarization in Convolutional Neural Networks"
date: 2018-05-25 21:21:32
categories: arXiv_CV
tags: arXiv_CV CNN
author: Josh Fromm, Shwetak Patel, Matthai Philipose
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that fast, compact low-bitwidth neural networks can be surprisingly accurate. These networks use homogeneous binarization: all parameters in each layer or (more commonly) the whole model have the same low bitwidth (e.g., 2 bits). However, modern hardware allows efficient designs where each arithmetic instruction can have a custom bitwidth, motivating heterogeneous binarization, where every parameter in the network may have a different bitwidth. In this paper, we show that it is feasible and useful to select bitwidths at the parameter granularity during training. For instance a heterogeneously quantized version of modern networks such as AlexNet and MobileNet, with the right mix of 1-, 2- and 3-bit parameters that average to just 1.4 bits can equal the accuracy of homogeneous 2-bit versions of these networks. Further, we provide analyses to show that the heterogeneously binarized systems yield FPGA- and ASIC-based implementations that are correspondingly more efficient in both circuit area and energy efficiency than their homogeneous counterparts.

##### Abstract (translated by Google)
最近的工作表明，快速，紧凑的低位宽度神经网络可以令人惊讶地准确。这些网络使用均匀的二进制化：每层或（更一般地）整个模型中的所有参数具有相同的低位宽度（例如2位）。然而，现代硬件允许有效的设计，其中每个算术指令可以具有自定义位宽，从而激励异构二进制化，其中网络中的每个参数可以具有不同的位宽。在本文中，我们表明在训练期间选择参数粒度的位宽是可行和有用的。例如，AlexNet和MobileNet等现代网络的异质量化版本以及平均只有1.4位的1位，2位和3位参数的正确组合可以等同于这些网络的同类2位版本的准确性。此外，我们提供的分析表明，非均匀二元化系统产生的FPGA和ASIC实现在电路面积和能效方面都比同类产品更高效。

##### URL
[http://arxiv.org/abs/1805.10368](http://arxiv.org/abs/1805.10368)

##### PDF
[http://arxiv.org/pdf/1805.10368](http://arxiv.org/pdf/1805.10368)

