---
layout: post
title: "Fast and Efficient Skin Detection for Facial Detection"
date: 2017-01-19 20:43:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative Detection
author: Mohammad Reza Mahmoodi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, an efficient skin detection system is proposed. The algorithm is based on a very fast efficient pre-processing step utilizing the concept of ternary conversion in order to identify candidate windows and subsequently, a novel local two-stage diffusion method which has F-score accuracy of 0.5978 on SDD dataset. The pre-processing step has been proven to be useful to boost the speed of the system by eliminating 82% of an image in average. This is obtained by keeping the true positive rate above 98%. In addition, a novel segmentation algorithm is also designed to process candidate windows which is quantitatively and qualitatively proven to be very efficient in term of accuracy. The algorithm has been implemented in FPGA to obtain real-time processing speed. The system is designed fully pipeline and the inherent parallel structure of the algorithm is fully exploited to maximize the performance. The system is implemented on a Spartan-6 LXT45 Xilinx FPGA and it is capable of processing 98 frames of 640*480 24-bit color images per second.

##### Abstract (translated by Google)
本文提出了一种高效的皮肤检测系统。该算法基于快速有效的预处理步骤，利用三元转换的概念来识别候选窗口，并且随后在SDD数据集上具有F评分精度为0.5978的新的局部两阶段扩散方法。预处理步骤已经被证明对于通过平均去除82％的图像来提高系统的速度是有用的。这是通过保持真正的阳性率达到98％以上。此外，还设计了一种新颖的分割算法来处理在定量和定性上被证明在准确性方面非常有效的候选窗口。该算法已经在FPGA中实现，以获得实时的处理速度。该系统设计完全流水线化，充分利用算法内在的并行结构，使性能最大化。该系统在Spartan-6 LXT45 Xilinx FPGA上实现，能够每秒处理98帧640 * 480的24位彩色图像。

##### URL
[https://arxiv.org/abs/1701.05595](https://arxiv.org/abs/1701.05595)

##### PDF
[https://arxiv.org/pdf/1701.05595](https://arxiv.org/pdf/1701.05595)

