---
layout: post
title: "ESE: Efficient Speech Recognition Engine with Sparse LSTM on FPGA"
date: 2017-02-20 06:28:58
categories: arXiv_CL
tags: arXiv_CL Sparse Speech_Recognition RNN Prediction Recognition
author: Song Han, Junlong Kang, Huizi Mao, Yiming Hu, Xin Li, Yubin Li, Dongliang Xie, Hong Luo, Song Yao, Yu Wang, Huazhong Yang, William J. Dally
mathjax: true
---

* content
{:toc}

##### Abstract
Long Short-Term Memory (LSTM) is widely used in speech recognition. In order to achieve higher prediction accuracy, machine learning scientists have built larger and larger models. Such large model is both computation intensive and memory intensive. Deploying such bulky model results in high power consumption and leads to high total cost of ownership (TCO) of a data center. In order to speedup the prediction and make it energy efficient, we first propose a load-balance-aware pruning method that can compress the LSTM model size by 20x (10x from pruning and 2x from quantization) with negligible loss of the prediction accuracy. The pruned model is friendly for parallel processing. Next, we propose scheduler that encodes and partitions the compressed model to each PE for parallelism, and schedule the complicated LSTM data flow. Finally, we design the hardware architecture, named Efficient Speech Recognition Engine (ESE) that works directly on the compressed model. Implemented on Xilinx XCKU060 FPGA running at 200MHz, ESE has a performance of 282 GOPS working directly on the compressed LSTM network, corresponding to 2.52 TOPS on the uncompressed one, and processes a full LSTM for speech recognition with a power dissipation of 41 Watts. Evaluated on the LSTM for speech recognition benchmark, ESE is 43x and 3x faster than Core i7 5930k CPU and Pascal Titan X GPU implementations. It achieves 40x and 11.5x higher energy efficiency compared with the CPU and GPU respectively.

##### Abstract (translated by Google)
长期短期记忆（LSTM）在语音识别中被广泛使用。为了达到更高的预测精度，机器学习科学家已经建立了越来越大的模型。这样大的模型既是计算密集型又是内存密集型的。部署这样庞大的模型会导致高功耗，并导致数据中心的总体拥有成本（TCO）较高。为了加速预测并提高能量效率，我们首先提出一种负载均衡感知的修剪方法，它可以将LSTM模型大小压缩20倍（从剪枝到10倍，从量化到2倍），而预测准确性可以忽略不计。修剪后的模型对于并行处理是友好的。接下来，我们提出了调度器，将压缩后的模型编码并分配给每个PE进行并行处理，并调度复杂的LSTM数据流。最后，我们设计了硬件架构，名为Efficient Speech Recognition Engine（ESE），它直接在压缩模型上工作。在运行频率为200MHz的Xilinx XCKU060 FPGA上实现，ESE具有282个GOPS性能，直接在压缩的LSTM网络上工作，对应于未压缩的2.52 TOPS，处理完整的语音识别LSTM，功耗为41瓦。在语音识别基准测试的LSTM上评估，ESE比Core i7 5930k CPU和Pascal Titan X GPU实现速度快43倍和3倍。与CPU和GPU相比，能效分别提高了40倍和11.5倍。

##### URL
[https://arxiv.org/abs/1612.00694](https://arxiv.org/abs/1612.00694)

##### PDF
[https://arxiv.org/pdf/1612.00694](https://arxiv.org/pdf/1612.00694)

