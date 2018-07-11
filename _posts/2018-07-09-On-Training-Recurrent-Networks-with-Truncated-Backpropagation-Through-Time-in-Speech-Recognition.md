---
layout: post
title: "On Training Recurrent Networks with Truncated Backpropagation Through Time in Speech Recognition"
date: 2018-07-09 21:31:49
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Prediction Recognition
author: Hao Tang, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have been the dominant models for many speech and language processing tasks. However, we understand little about the behavior and the class of functions recurrent networks can realize. Moreover, the heuristics used during training complicate the analyses. In this paper, we study recurrent networks' ability to learn long-term dependency in the context of speech recognition. We consider two decoding approaches, online and batch decoding, and show the classes of functions to which the decoding approaches correspond. We then draw a connection between batch decoding and a popular training approach for recurrent networks, truncated backpropagation through time. Changing the decoding approach restricts the amount of past history recurrent networks can use for prediction, allowing us to analyze their ability to remember. Empirically, we utilize long-term dependency in subphonetic states, phonemes, and words, and show how the design decisions, such as the decoding approach, lookahead, context frames, and consecutive prediction, characterize the behavior of recurrent networks. Finally, we draw a connection between Markov processes and vanishing gradients. These results have implications for studying the long-term dependency in speech data and how these properties are learned by recurrent networks.

##### Abstract (translated by Google)
循环神经网络已成为许多语音和语言处理任务的主导模型。但是，我们对循环网络可以实现的行为和功能类别了解甚少。此外，训练期间使用的启发式方法使分析复杂化。在本文中，我们研究了复发网络在语音识别环境中学习长期依赖的能力。我们考虑两种解码方法，在线和批量解码，并显示解码方法所对应的功能类别。然后，我们在批量解码和常规网络的流行训练方法之间建立联系，随着时间的推移截断反向传播。更改解码方法会限制经常性网络可用于预测的过去历史数量，从而允许我们分析其记忆能力。根据经验，我们利用亚音状态，音素和单词的长期依赖性，并展示设计决策（如解码方法，前瞻，上下文帧和连续预测）如何表征循环网络的行为。最后，我们在马尔可夫过程和消失的梯度之间建立了联系。这些结果对于研究语音数据的长期依赖性以及如何通过循环网络学习这些属性具有意义。

##### URL
[http://arxiv.org/abs/1807.03396](http://arxiv.org/abs/1807.03396)

##### PDF
[http://arxiv.org/pdf/1807.03396](http://arxiv.org/pdf/1807.03396)

