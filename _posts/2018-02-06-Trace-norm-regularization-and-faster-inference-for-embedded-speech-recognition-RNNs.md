---
layout: post
title: "Trace norm regularization and faster inference for embedded speech recognition RNNs"
date: 2018-02-06 10:00:10
categories: arXiv_CL
tags: arXiv_CL Regularization Speech_Recognition Inference RNN Recognition
author: Markus Kliegl, Siddharth Goyal, Kexin Zhao, Kavya Srinet, Mohammad Shoeybi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose and evaluate new techniques for compressing and speeding up dense matrix multiplications as found in the fully connected and recurrent layers of neural networks for embedded large vocabulary continuous speech recognition (LVCSR). For compression, we introduce and study a trace norm regularization technique for training low rank factored versions of matrix multiplications. Compared to standard low rank training, we show that our method leads to good accuracy versus number of parameter trade-offs and can be used to speed up training of large models. For speedup, we enable faster inference on ARM processors through new open sourced kernels optimized for small batch sizes, resulting in 3x to 7x speed ups over the widely used gemmlowp library. Beyond LVCSR, we expect our techniques and kernels to be more generally applicable to embedded neural networks with large fully connected or recurrent layers.

##### Abstract (translated by Google)
我们提出并评估压缩和加速密集矩阵乘法的新技术，如在用于嵌入式大词汇量连续语音识别（LVCSR）的完全连接的和递归的神经网络层中发现的。为了压缩，我们引入和研究用于训练矩阵乘法的低秩因式版本的跟踪范数正则化技术。与标准的低阶训练相比，我们证明了我们的方法相对于参数权衡的数量导致了很好的准确性，并且可以用来加速大型模型的训练。为了加快速度，我们通过针对小批量大小优化的新型开源内核，在ARM处理器上实现了更快的推断，从而使得广泛使用的gemmlowp库的速度提高了3倍到7倍。除LVCSR之外，我们期望我们的技术和内核更一般地适用于具有大的完全连接或重复层的嵌入式神经网络。

##### URL
[http://arxiv.org/abs/1710.09026](http://arxiv.org/abs/1710.09026)

##### PDF
[http://arxiv.org/pdf/1710.09026](http://arxiv.org/pdf/1710.09026)

