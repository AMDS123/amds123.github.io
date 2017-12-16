---
layout: post
title: "Effective Quantization Methods for Recurrent Neural Networks"
date: 2016-11-30 14:33:08
categories: arXiv_CV
tags: arXiv_CV Inference RNN
author: Qinyao He, He Wen, Shuchang Zhou, Yuxin Wu, Cong Yao, Xinyu Zhou, Yuheng Zou
mathjax: true
---

* content
{:toc}

##### Abstract
Reducing bit-widths of weights, activations, and gradients of a Neural Network can shrink its storage size and memory usage, and also allow for faster training and inference by exploiting bitwise operations. However, previous attempts for quantization of RNNs show considerable performance degradation when using low bit-width weights and activations. In this paper, we propose methods to quantize the structure of gates and interlinks in LSTM and GRU cells. In addition, we propose balanced quantization methods for weights to further reduce performance degradation. Experiments on PTB and IMDB datasets confirm effectiveness of our methods as performances of our models match or surpass the previous state-of-the-art of quantized RNN.

##### Abstract (translated by Google)
减少神经网络的权重，激活和梯度的位宽可以缩小其存储大小和内存使用量，并且还允许通过利用逐位操作来加快训练和推断。然而，以前的量化RNN的尝试在使用低位宽度权重和激活时显示出相当大的性能下降。在本文中，我们提出了量化LSTM和GRU单元中门和链路结构的方法。另外，我们提出了权重的均衡量化方法，以进一步降低性能下降。 PTB和IMDB数据集上的实验证实了我们的方法的有效性，因为我们的模型的性能匹配或超过了先前的量化的RNN。

##### URL
[https://arxiv.org/abs/1611.10176](https://arxiv.org/abs/1611.10176)

##### PDF
[https://arxiv.org/pdf/1611.10176](https://arxiv.org/pdf/1611.10176)

