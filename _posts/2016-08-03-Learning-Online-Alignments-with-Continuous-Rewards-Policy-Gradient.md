---
layout: post
title: "Learning Online Alignments with Continuous Rewards Policy Gradient"
date: 2016-08-03 18:35:12
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Inference Recognition
author: Yuping Luo, Chung-Cheng Chiu, Navdeep Jaitly, Ilya Sutskever
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models with soft attention had significant success in machine translation, speech recognition, and question answering. Though capable and easy to use, they require that the entirety of the input sequence is available at the beginning of inference, an assumption that is not valid for instantaneous translation and speech recognition. To address this problem, we present a new method for solving sequence-to-sequence problems using hard online alignments instead of soft offline alignments. The online alignments model is able to start producing outputs without the need to first process the entire input sequence. A highly accurate online sequence-to-sequence model is useful because it can be used to build an accurate voice-based instantaneous translator. Our model uses hard binary stochastic decisions to select the timesteps at which outputs will be produced. The model is trained to produce these stochastic decisions using a standard policy gradient method. In our experiments, we show that this model achieves encouraging performance on TIMIT and Wall Street Journal (WSJ) speech recognition datasets.

##### Abstract (translated by Google)
在机器翻译，语音识别和问题回答方面，顺序到顺序的模型受到了人们的关注。虽然能够使用并且易于使用，但是它们要求在推断开始时整个输入序列是可用的，这对于即时翻译和语音识别是无效的假设。为了解决这个问题，我们提出了一个新的方法来解决序列到序列问题，而不是软离线对齐。在线对准模型能够开始产生输出，而不需要首先处理整个输入序列。高度精确的在线序列到序列模型是有用的，因为它可以用来构建准确的基于语音的瞬时翻译器。我们的模型使用硬二元随机决策来选择产生输出的时间步长。训练该模型以使用标准策略梯度方法产生这些随机决定。在我们的实验中，我们显示这个模型在TIMIT和华尔街日报（WSJ）语音识别数据集上取得了令人鼓舞的表现。

##### URL
[https://arxiv.org/abs/1608.01281](https://arxiv.org/abs/1608.01281)

##### PDF
[https://arxiv.org/pdf/1608.01281](https://arxiv.org/pdf/1608.01281)

