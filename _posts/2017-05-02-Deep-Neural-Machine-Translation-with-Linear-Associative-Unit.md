---
layout: post
title: "Deep Neural Machine Translation with Linear Associative Unit"
date: 2017-05-02 08:58:17
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Mingxuan Wang, Zhengdong Lu, Jie Zhou, Qun Liu
---

* content
{:toc}

##### Abstract
Deep Neural Networks (DNNs) have provably enhanced the state-of-the-art Neural Machine Translation (NMT) with their capability in modeling complex functions and capturing complex linguistic structures. However NMT systems with deep architecture in their encoder or decoder RNNs often suffer from severe gradient diffusion due to the non-linear recurrent activations, which often make the optimization much more difficult. To address this problem we propose novel linear associative units (LAU) to reduce the gradient propagation length inside the recurrent unit. Different from conventional approaches (LSTM unit and GRU), LAUs utilizes linear associative connections between input and output of the recurrent unit, which allows unimpeded information flow through both space and time direction. The model is quite simple, but it is surprisingly effective. Our empirical study on Chinese-English translation shows that our model with proper configuration can improve by 11.7 BLEU upon Groundhog and the best reported results in the same setting. On WMT14 English-German task and a larger WMT14 English-French task, our model achieves comparable results with the state-of-the-art.

##### Abstract (translated by Google)
深度神经网络（DNNs）凭借其在复杂功能建模和捕捉复杂语言结构方面的能力，已经证明可以增强最先进的神经机器翻译（NMT）。然而，在编码器或解码器RNN中具有深度架构的NMT系统由于非线性复发激活而经常遭受严重的梯度扩散，这经常使得优化更加困难。为了解决这个问题，我们提出了新的线性关联单元（LAU）来减少递归单元内的梯度传播长度。与常规方法（LSTM单元和GRU）不同，LAU利用递归单元的输入和输出之间的线性关联连接，允许不受阻碍的信息在空间和时间方向上流动。这个模型非常简单，但是却非常有效。我们对汉英翻译的实证研究表明，具有适当配置的模型在土拨鼠上可以提高11.7个BLEU，在相同的情况下报告结果最好。在WMT14英德任务和更大的WMT14英法任务中，我们的模型与最先进的技术达到了可比的结果。

##### URL
[https://arxiv.org/abs/1705.00861](https://arxiv.org/abs/1705.00861)

