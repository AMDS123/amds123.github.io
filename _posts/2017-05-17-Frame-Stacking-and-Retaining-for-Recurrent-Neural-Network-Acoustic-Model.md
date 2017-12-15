---
layout: post
title: "Frame Stacking and Retaining for Recurrent Neural Network Acoustic Model"
date: 2017-05-17 02:34:27
categories: arXiv_CL
tags: arXiv_CL RNN Classification Recognition
author: Xu Tian, Jun Zhang, Zejun Ma, Yi He, Juan Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Frame stacking is broadly applied in end-to-end neural network training like connectionist temporal classification (CTC), and it leads to more accurate models and faster decoding. However, it is not well-suited to conventional neural network based on context-dependent state acoustic model, if the decoder is unchanged. In this paper, we propose a novel frame retaining method which is applied in decoding. The system which combined frame retaining with frame stacking could reduces the time consumption of both training and decoding. Long short-term memory (LSTM) recurrent neural networks (RNNs) using it achieve almost linear training speedup and reduces relative 41\% real time factor (RTF). At the same time, recognition performance is no degradation or improves sightly on Shenma voice search dataset in Mandarin.

##### Abstract (translated by Google)
框架叠加广泛应用于连接主义时间分类（CTC）等端到端的神经网络训练，并导致更精确的模型和更快的解码。然而，如果解码器不变，则它不适合于基于上下文相关状态声学模型的传统神经网络。在本文中，我们提出了一种新的帧保留方法，用于解码。将帧保留与帧叠加相结合的系统可以减少训练和解码的时间消耗。使用它的长期短期记忆（LSTM）递归神经网络（RNN）实现了几乎线性的训练加速并减少了相对41％的实时因子（RTF）。与此同时，普通话中的神马语音搜索数据集的识别性能没有降低或明显提高。

##### URL
[https://arxiv.org/abs/1705.05992](https://arxiv.org/abs/1705.05992)

##### PDF
[https://arxiv.org/pdf/1705.05992](https://arxiv.org/pdf/1705.05992)

