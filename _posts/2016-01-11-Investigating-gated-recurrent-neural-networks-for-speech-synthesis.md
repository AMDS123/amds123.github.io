---
layout: post
title: "Investigating gated recurrent neural networks for speech synthesis"
date: 2016-01-11 17:54:53
categories: arXiv_SD
tags: arXiv_SD RNN
author: Zhizheng Wu, Simon King
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, recurrent neural networks (RNNs) as powerful sequence models have re-emerged as a potential acoustic model for statistical parametric speech synthesis (SPSS). The long short-term memory (LSTM) architecture is particularly attractive because it addresses the vanishing gradient problem in standard RNNs, making them easier to train. Although recent studies have demonstrated that LSTMs can achieve significantly better performance on SPSS than deep feed-forward neural networks, little is known about why. Here we attempt to answer two questions: a) why do LSTMs work well as a sequence model for SPSS; b) which component (e.g., input gate, output gate, forget gate) is most important. We present a visual analysis alongside a series of experiments, resulting in a proposal for a simplified architecture. The simplified architecture has significantly fewer parameters than an LSTM, thus reducing generation complexity considerably without degrading quality.

##### Abstract (translated by Google)
最近，递归神经网络（RNN）作为强大的序列模型已经重新成为统计参数语音合成（SPSS）的潜在声学模型。长期的短期记忆（LSTM）体系结构特别吸引人，因为它解决了标准RNN中消失的梯度问题，使得它们更易于训练。虽然最近的研究已经证明LSTM可以在深度前馈神经网络上获得显着更好的SPSS性能，但为什么还不知道。在这里，我们试图回答两个问题：a）为什么LSTM作为SPSS的序列模型运行良好; b）哪个组件（例如，输入门，输出门，忘记门）是最重要的。我们展示了一系列实验的可视化分析结果，提出了一个简化的架构。与LSTM相比，简化架构的参数显着减少，从而大大降低了发电复杂性，而不会降低质量。

##### URL
[https://arxiv.org/abs/1601.02539](https://arxiv.org/abs/1601.02539)

##### PDF
[https://arxiv.org/pdf/1601.02539](https://arxiv.org/pdf/1601.02539)

