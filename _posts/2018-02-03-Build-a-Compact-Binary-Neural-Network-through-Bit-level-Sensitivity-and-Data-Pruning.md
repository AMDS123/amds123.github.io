---
layout: post
title: "Build a Compact Binary Neural Network through Bit-level Sensitivity and Data Pruning"
date: 2018-02-03 03:50:41
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yixing Li, Fengbo Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) has been widely used for vision-based tasks. Due to the high computational complexity and memory storage requirement, it is hard to directly deploy a full-precision CNN on embedded devices. The hardware-friendly designs are needed for re-source-limited and energy-constrained embed-ded devices. Emerging solutions are adopted for the neural network compression, e.g., bina-ry/ternary weight network, pruned network and quantized network. Among them, Binarized Neural Network (BNN) is believed to be the most hardware-friendly framework due to its small network size and low computational com-plexity. No existing work has further shrunk the size of BNN. In this work, we explore the redun-dancy in BNN and build a compact BNN (CBNN) based on the bit-level sensitivity analy-sis and bit-level data pruning. The input data is converted to a high dimensional bit-sliced for-mat. In post-training stage, we analyze the im-pact of different bit slices to the accuracy. By pruning the redundant input bit slices and shrinking the network size, we are able to build a more compact BNN. Our result shows that we can further scale down the network size of the BNN up to 3.9x with no more than 1% accuracy drop. The actual runtime can be reduced up to 2x and 9.9x compared with the baseline BNN and its full-precision counterpart, respectively.

##### Abstract (translated by Google)
卷积神经网络（CNN）已被广泛用于基于视觉的任务。由于高计算复杂度和内存需求，很难在嵌入式设备上直接部署全精度CNN。对于重新限制源和限制能量的嵌入式设备，需要硬件友好的设计。神经网络压缩采用新兴的解决方案，例如二进制/三进制加权网络，修剪网络和量化网络。其中，二值化神经网络（BNN）由于网络规模小，计算复杂度低而被认为是硬件友好性最高的框架。现有的工作没有进一步缩小BNN的规模。在这个工作中，我们研究BNN中的redundancy，并且建立一个基于位级敏感性分析和位级数据修剪的紧凑BNN（CBNN）。输入数据被转换成高维比特分片格式。在训练后阶段，我们分析了不同位片的影响对精度的影响。通过修剪冗余输入位片并缩小网络大小，我们可以构建更紧凑的BNN。我们的结果显示，我们可以将BNN的网络规模进一步缩小到3.9倍，精度下降不超过1％。实际的运行时间可以分别比基线BNN和其全精度对应减少2倍和9.9倍。

##### URL
[http://arxiv.org/abs/1802.00904](http://arxiv.org/abs/1802.00904)

##### PDF
[http://arxiv.org/pdf/1802.00904](http://arxiv.org/pdf/1802.00904)

