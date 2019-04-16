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


##### URL
[https://arxiv.org/abs/1602.01616](https://arxiv.org/abs/1602.01616)

##### PDF
[https://arxiv.org/pdf/1602.01616](https://arxiv.org/pdf/1602.01616)

