---
layout: post
title: "FPGA-Based Low-Power Speech Recognition with Recurrent Neural Networks"
date: 2016-09-30 10:44:32
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Minjae Lee, Kyuyeon Hwang, Jinhwan Park, Sungwook Choi, Sungho Shin, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a neural network based real-time speech recognition (SR) system is developed using an FPGA for very low-power operation. The implemented system employs two recurrent neural networks (RNNs); one is a speech-to-character RNN for acoustic modeling (AM) and the other is for character-level language modeling (LM). The system also employs a statistical word-level LM to improve the recognition accuracy. The results of the AM, the character-level LM, and the word-level LM are combined using a fairly simple N-best search algorithm instead of the hidden Markov model (HMM) based network. The RNNs are implemented using massively parallel processing elements (PEs) for low latency and high throughput. The weights are quantized to 6 bits to store all of them in the on-chip memory of an FPGA. The proposed algorithm is implemented on a Xilinx XC7Z045, and the system can operate much faster than real-time.

##### Abstract (translated by Google)
在本文中，基于神经网络的实时语音识别（SR）系统是使用FPGA开发的，用于非常低功耗的操作。实施的系统采用两个循环神经网络（RNN）;一个是用于声学建模（AM）的语音到字符RNN，另一个是用于字符级语言建模（LM）的。系统还采用统计字级LM来提高识别的准确性。 AM，字符级LM和单词级LM的结果使用相当简单的N最佳搜索算法而不是基于隐马尔可夫模型（HMM）的网络来组合。 RNN是使用大规模并行处理单元（PE）实现的，以实现低延迟和高吞吐量。将权重量化为6位，将其全部存储在FPGA的片上存储器中。所提出的算法在Xilinx XC7Z045上实现，系统运行速度比实时快。

##### URL
[https://arxiv.org/abs/1610.00552](https://arxiv.org/abs/1610.00552)

##### PDF
[https://arxiv.org/pdf/1610.00552](https://arxiv.org/pdf/1610.00552)

