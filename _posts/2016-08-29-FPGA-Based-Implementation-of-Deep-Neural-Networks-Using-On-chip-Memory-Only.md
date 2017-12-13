---
layout: post
title: "FPGA Based Implementation of Deep Neural Networks Using On-chip Memory Only"
date: 2016-08-29 06:24:25
categories: arXiv_CV
tags: arXiv_CV Optimization Recognition
author: Jinhwan Park, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) demand a very large amount of computation and weight storage, and thus efficient implementation using special purpose hardware is highly desired. In this work, we have developed an FPGA based fixed-point DNN system using only on-chip memory not to access external DRAM. The execution time and energy consumption of the developed system is compared with a GPU based implementation. Since the capacity of memory in FPGA is limited, only 3-bit weights are used for this implementation, and training based fixed-point weight optimization is employed. The implementation using Xilinx XC7Z045 is tested for the MNIST handwritten digit recognition benchmark and a phoneme recognition task on TIMIT corpus. The obtained speed is about one quarter of a GPU based implementation and much better than that of a PC based one. The power consumption is less than 5 Watt at the full speed operation resulting in much higher efficiency compared to GPU based systems.

##### Abstract (translated by Google)
深度神经网络（DNN）需要非常大量的计算和重量存储，因此高度期望使用专用硬件的有效实现。在这项工作中，我们开发了一种基于FPGA的定点DNN系统，仅使用片上存储器不能访问外部DRAM。开发系统的执行时间和能耗与基于GPU的实现进行比较。由于FPGA存储器的容量有限，所以实现时只使用3位权重，采用基于训练的定点权重优化。对使用Xilinx XC7Z045的实现进行了MNIST手写数字识别基准测试和TIMIT语料库上的音素识别任务测试。获得的速度大约是基于GPU的实施的四分之一，并且比基于PC的实施要好得多。全速运行时功耗小于5瓦，与基于GPU的系统相比效率更高。

##### URL
[https://arxiv.org/abs/1602.01616](https://arxiv.org/abs/1602.01616)

##### PDF
[https://arxiv.org/pdf/1602.01616](https://arxiv.org/pdf/1602.01616)

