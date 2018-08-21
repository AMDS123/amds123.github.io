---
layout: post
title: "A study on speech enhancement using exponent-only floating point quantized neural network"
date: 2018-08-17 11:44:34
categories: arXiv_AI
tags: arXiv_AI CNN RNN Classification
author: Yi-Te Hsu, Yu-Chen Lin, Szu-Wei Fu, Yu Tsao, Tei-Wei Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Numerous studies have investigated the effectiveness of neural network quantization on pattern classification tasks. The present study, for the first time, investigated the performance of speech enhancement (a regression task in speech processing) using a novel exponent-only floating-point quantized neural network (EOFP-QNN). The proposed EOFP-QNN consists of two stages: mantissa-quantization and exponent-quantization. In the mantissa-quantization stage, EOFP-QNN learns how to quantize the mantissa bits of the model parameters while preserving the regression accuracy in the least mantissa precision. In the exponent-quantization stage, the exponent part of the parameters is further quantized without any additional performance degradation. We evaluated the proposed EOFP quantization technique on two types of neural networks, namely, bidirectional long short-term memory (BLSTM) and fully convolutional neural network (FCN), on a speech enhancement task. Experimental results showed that the model sizes can be significantly reduced (the model sizes of the quantized BLSTM and FCN models were only 18.75% and 21.89%, respectively, compared to those of the original models) while maintaining a satisfactory speech-enhancement performance.

##### Abstract (translated by Google)
大量研究已经研究了神经网络量化对模式分类任务的有效性。本研究首次使用新的无指数浮点量化神经网络（EOFP-QNN）研究了语音增强（语音处理中的回归任务）的性能。所提出的EOFP-QNN包括两个阶段：尾数量化和指数量化。在尾数量化阶段，EOFP-QNN学习如何量化模型参数的尾数位，同时保持最小尾数精度的回归精度。在指数量化阶段，参数的指数部分被进一步量化，而没有任何额外的性能下降。我们在语音增强任务上评估了两种神经网络上提出的EOFP量化技术，即双向长短期记忆（BLSTM）和完全卷积神经网络（FCN）。实验结果表明，模型尺寸可以显着减小（量化BLSTM和FCN模型的模型尺寸分别仅为原始模型的18.75％和21.89％），同时保持令人满意的语音增强性能。

##### URL
[http://arxiv.org/abs/1808.06474](http://arxiv.org/abs/1808.06474)

##### PDF
[http://arxiv.org/pdf/1808.06474](http://arxiv.org/pdf/1808.06474)

