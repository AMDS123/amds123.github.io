---
layout: post
title: "Quantized Memory-Augmented Neural Networks"
date: 2017-11-10 06:54:45
categories: arXiv_CV
tags: arXiv_CV CNN Inference RNN Memory_Networks
author: Seongsik Park, Seijoon Kim, Seil Lee, Ho Bae, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Memory-augmented neural networks (MANNs) refer to a class of neural network models equipped with external memory (such as neural Turing machines and memory networks). These neural networks outperform conventional recurrent neural networks (RNNs) in terms of learning long-term dependency, allowing them to solve intriguing AI tasks that would otherwise be hard to address. This paper concerns the problem of quantizing MANNs. Quantization is known to be effective when we deploy deep models on embedded systems with limited resources. Furthermore, quantization can substantially reduce the energy consumption of the inference procedure. These benefits justify recent developments of quantized multi layer perceptrons, convolutional networks, and RNNs. However, no prior work has reported the successful quantization of MANNs. The in-depth analysis presented here reveals various challenges that do not appear in the quantization of the other networks. Without addressing them properly, quantized MANNs would normally suffer from excessive quantization error which leads to degraded performance. In this paper, we identify memory addressing (specifically, content-based addressing) as the main reason for the performance degradation and propose a robust quantization method for MANNs to address the challenge. In our experiments, we achieved a computation-energy gain of 22x with 8-bit fixed-point and binary quantization compared to the floating-point implementation. Measured on the bAbI dataset, the resulting model, named the quantized MANN (Q-MANN), improved the error rate by 46% and 30% with 8-bit fixed-point and binary quantization, respectively, compared to the MANN quantized using conventional techniques.

##### Abstract (translated by Google)
记忆增强神经网络（MANNs）是指配备有外部存储器（如神经图灵机和记忆网络）的一类神经网络模型。这些神经网络在学习长期依赖性方面优于传统的递归神经网络（RNN），使他们能够解决难以解决的有趣的AI任务。本文涉及量化MANNs的问题。当我们在资源有限的嵌入式系统上部署深度模型时，量化被认为是有效的。而且，量化可以大大减少推理过程的能量消耗。这些好处证明了量子化多层感知器，卷积网络和RNN的最新发展。然而，以前的工作没有报道成功量化MANNs。这里给出的深入分析揭示了在其他网络的量化中没有出现的各种挑战。如果不正确地解决这些问题，量化的MANN通常会遭受过度的量化误差，从而导致性能下降。在本文中，我们将存储器寻址（具体来说，基于内容的寻址）确定为性能下降的主要原因，并提出一种用于MANNs的鲁棒量化方法来应对这一挑战。在我们的实验中，与浮点实现相比，我们使用8位定点和二进制量化实现了22倍的计算能量增益。在bAbI数据集上测量，与使用常规量化的MANN相比，所得到的称为量化MANN（Q-MANN）的模型分别使用8比特定点和二进制量化将错误率分别提高了46％和30％技术。

##### URL
[https://arxiv.org/abs/1711.03712](https://arxiv.org/abs/1711.03712)

##### PDF
[https://arxiv.org/pdf/1711.03712](https://arxiv.org/pdf/1711.03712)

