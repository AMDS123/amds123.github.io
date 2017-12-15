---
layout: post
title: "On the efficient representation and execution of deep acoustic models"
date: 2016-12-17 01:31:31
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Inference Recognition
author: Raziel Alvarez, Rohit Prabhavalkar, Anton Bakhtin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a simple and computationally efficient quantization scheme that enables us to reduce the resolution of the parameters of a neural network from 32-bit floating point values to 8-bit integer values. The proposed quantization scheme leads to significant memory savings and enables the use of optimized hardware instructions for integer arithmetic, thus significantly reducing the cost of inference. Finally, we propose a "quantization aware" training process that applies the proposed scheme during network training and find that it allows us to recover most of the loss in accuracy introduced by quantization. We validate the proposed techniques by applying them to a long short-term memory-based acoustic model on an open-ended large vocabulary speech recognition task.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单而计算效率高的量化方案，使我们能够将神经网络参数的分辨率从32位浮点值降低到8位整数值。所提出的量化方案导致显着的存储器节省，并且使得能够使用优化的硬件指令来进行整数运算，从而显着降低了推理的成本。最后，我们提出了一个“量化意识”的训练过程，在网络训练期间应用所提出的方案，并发现它使我们能够恢复由量化引入的大部分精度损失。我们验证提出的技术，将其应用于开放式大词汇量语音识别任务中的基于记忆的长期声学模型。

##### URL
[https://arxiv.org/abs/1607.04683](https://arxiv.org/abs/1607.04683)

##### PDF
[https://arxiv.org/pdf/1607.04683](https://arxiv.org/pdf/1607.04683)

