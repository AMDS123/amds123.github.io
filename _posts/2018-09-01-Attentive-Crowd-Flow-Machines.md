---
layout: post
title: "Attentive Crowd Flow Machines"
date: 2018-09-01 02:22:57
categories: arXiv_CV
tags: arXiv_CV Attention CNN Inference RNN Prediction
author: Lingbo Liu, Ruimao Zhang, Jiefeng Peng, Guanbin Li, Bowen Du, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Traffic flow prediction is crucial for urban traffic management and public safety. Its key challenges lie in how to adaptively integrate the various factors that affect the flow changes. In this paper, we propose a unified neural network module to address this problem, called Attentive Crowd Flow Machine~(ACFM), which is able to infer the evolution of the crowd flow by learning dynamic representations of temporally-varying data with an attention mechanism. Specifically, the ACFM is composed of two progressive ConvLSTM units connected with a convolutional layer for spatial weight prediction. The first LSTM takes the sequential flow density representation as input and generates a hidden state at each time-step for attention map inference, while the second LSTM aims at learning the effective spatial-temporal feature expression from attentionally weighted crowd flow features. Based on the ACFM, we further build a deep architecture with the application to citywide crowd flow prediction, which naturally incorporates the sequential and periodic data as well as other external influences. Extensive experiments on two standard benchmarks (i.e., crowd flow in Beijing and New York City) show that the proposed method achieves significant improvements over the state-of-the-art methods.

##### Abstract (translated by Google)
交通流量预测对城市交通管理和公共安全至关重要。其主要挑战在于如何自适应地整合影响流量变化的各种因素。在本文中，我们提出了一个统一的神经网络模块来解决这个问题，称为Attentive Crowd Flow Machine~（ACFM），它能够通过用注意机制学习时变数据的动态表示来推断人群流的演变。 。具体地，ACFM由两个渐进式ConvLSTM单元组成，其与卷积层连接以用于空间权重预测。第一个LSTM将顺序流密度表示作为输入，并在每个时间步骤生成隐藏状态以用于注意力图推断，而第二个LSTM旨在从注意加权的人群流特征中学习有效的时空特征表达。基于ACFM，我们进一步构建了一个深层架构，应用于全市人群流量预测，自然地包含顺序和周期性数据以及其他外部影响。在两个标准基准（即北京和纽约市的人群流动）上的广泛实验表明，所提出的方法相对于最先进的方法实现了显着的改进。

##### URL
[http://arxiv.org/abs/1809.00101](http://arxiv.org/abs/1809.00101)

##### PDF
[http://arxiv.org/pdf/1809.00101](http://arxiv.org/pdf/1809.00101)

