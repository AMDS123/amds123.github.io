---
layout: post
title: "FINN-L: Library Extensions and Design Trade-off Analysis for Variable Precision LSTM Networks on FPGAs"
date: 2018-07-11 11:52:59
categories: arXiv_CV
tags: arXiv_CV RNN Classification Recognition
author: Vladimir Rybalkin, Alessandro Pappalardo, Muhammad Mohsin Ghaffar, Giulio Gambardella, Norbert Wehn, Michaela Blott
mathjax: true
---

* content
{:toc}

##### Abstract
It is well known that many types of artificial neural networks, including recurrent networks, can achieve a high classification accuracy even with low-precision weights and activations. The reduction in precision generally yields much more efficient hardware implementations in regards to hardware cost, memory requirements, energy, and achievable throughput. In this paper, we present the first systematic exploration of this design space as a function of precision for Bidirectional Long Short-Term Memory (BiLSTM) neural network. Specifically, we include an in-depth investigation of precision vs. accuracy using a fully hardware-aware training flow, where during training quantization of all aspects of the network including weights, input, output and in-memory cell activations are taken into consideration. In addition, hardware resource cost, power consumption and throughput scalability are explored as a function of precision for FPGA-based implementations of BiLSTM, and multiple approaches of parallelizing the hardware. We provide the first open source HLS library extension of FINN for parameterizable hardware architectures of LSTM layers on FPGAs which offers full precision flexibility and allows for parameterizable performance scaling offering different levels of parallelism within the architecture. Based on this library, we present an FPGA-based accelerator for BiLSTM neural network designed for optical character recognition, along with numerous other experimental proof points for a Zynq UltraScale+ XCZU7EV MPSoC within the given design space.

##### Abstract (translated by Google)
众所周知，即使使用低精度权重和激活，许多类型的人工神经网络（包括循环网络）也可以实现高分类精度。精度的降低通常在硬件成本，存储器要求，能量和可实现的吞吐量方面产生更有效的硬件实现。在本文中，我们首次系统地探索了这个设计空间作为双向长短期记忆（BiLSTM）神经网络精度的函数。具体而言，我们使用完全硬件感知的培训流程对精确度与准确度进行深入研究，其中在训练期间考虑网络的所有方面的量化，包括权重，输入，输出和存储器内单元激活。此外，还探讨了硬件资源成本，功耗和吞吐量可扩展性，作为基于FPGA的BiLSTM实现的精确度的函数，以及多种并行化硬件的方法。我们提供FINN的第一个开源HLS库扩展，用于FPGA上LSTM层的可参数化硬件架构，提供全精度灵活性，并允许参数化性能扩展，在架构内提供不同级别的并行性。基于该库，我们提供了一个基于FPGA的BiLSTM神经网络加速器，用于光学字符识别，以及在给定设计空间内Zynq UltraScale + XCZU7EV MPSoC的许多其他实验验证点。

##### URL
[http://arxiv.org/abs/1807.04093](http://arxiv.org/abs/1807.04093)

##### PDF
[http://arxiv.org/pdf/1807.04093](http://arxiv.org/pdf/1807.04093)

