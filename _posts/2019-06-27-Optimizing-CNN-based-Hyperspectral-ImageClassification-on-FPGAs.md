---
layout: post
title: "Optimizing CNN-based Hyperspectral ImageClassification on FPGAs"
date: 2019-06-27 22:05:22
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Shuanglong Liu, Ringo S.W. Chu, Xiwei Wang, Wayne Luk
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral image (HSI) classification has been widely adopted in applications involving remote sensing imagery analysis which require high classification accuracy and real-time processing speed. Methods based on Convolutional neural networks (CNNs) have been proven to achieve state-of-the-art accuracy in classifying HSIs. However, CNN models are often too computationally intensive to achieve real-time response due to the high dimensional nature of HSI, compared to traditional methods such as Support Vector Machines (SVMs). Besides, previous CNN models used in HSI are not specially designed for efficient implementation on embedded devices such as FPGAs. This paper proposes a novel CNN-based algorithm for HSI classification which takes into account hardware efficiency. A customized architecture which enables the proposed algorithm to be mapped effectively onto FPGA resources is then proposed to support real-time on-board classification with low power consumption. Implementation results show that our proposed accelerator on a Xilinx Zynq 706 FPGA board achieves more than 70x faster than an Intel 8-core Xeon CPU and 3x faster than an NVIDIA GeForce 1080 GPU. Compared to previous SVM-based FPGA accelerators, we achieve comparable processing speed but provide a much higher classification accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11834](http://arxiv.org/abs/1906.11834)

##### PDF
[http://arxiv.org/pdf/1906.11834](http://arxiv.org/pdf/1906.11834)

