---
layout: post
title: "Image Question Answering using Convolutional Neural Network with Dynamic Parameter Prediction"
date: 2015-11-18 12:30:57
categories: arXiv_CL
tags: arXiv_CL QA CNN Prediction
author: Hyeonwoo Noh, Paul Hongsuck Seo, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle image question answering (ImageQA) problem by learning a convolutional neural network (CNN) with a dynamic parameter layer whose weights are determined adaptively based on questions. For the adaptive parameter prediction, we employ a separate parameter prediction network, which consists of gated recurrent unit (GRU) taking a question as its input and a fully-connected layer generating a set of candidate weights as its output. However, it is challenging to construct a parameter prediction network for a large number of parameters in the fully-connected dynamic parameter layer of the CNN. We reduce the complexity of this problem by incorporating a hashing technique, where the candidate weights given by the parameter prediction network are selected using a predefined hash function to determine individual weights in the dynamic parameter layer. The proposed network---joint network with the CNN for ImageQA and the parameter prediction network---is trained end-to-end through back-propagation, where its weights are initialized using a pre-trained CNN and GRU. The proposed algorithm illustrates the state-of-the-art performance on all available public ImageQA benchmarks.

##### Abstract (translated by Google)
我们通过学习卷积神经网络（CNN）来解决图像问题回答（ImageQA）问题，其中动态参数层的权重是根据问题自适应确定的。对于自适应参数预测，我们采用一个单独的参数预测网络，其中包含以问题为输入的门控回归单元（GRU）和产生一组候选权重作为其输出的全连接层。然而，为CNN的全连接动态参数层中的大量参数构建参数预测网络是具有挑战性的。我们通过引入散列技术来降低这个问题的复杂度，其中通过使用预定义的散列函数来选择由参数预测网络给出的候选权重，以确定动态参数层中的各个权重。所提出的网络---与CNN的ImageQA联合网络和参数预测网络---通过反向传播进行端对端的训练，其权重使用预先训练的CNN和GRU进行初始化。所提出的算法说明了所有可用的公共ImageQA基准测试中的最新性能。

##### URL
[https://arxiv.org/abs/1511.05756](https://arxiv.org/abs/1511.05756)

##### PDF
[https://arxiv.org/pdf/1511.05756](https://arxiv.org/pdf/1511.05756)

