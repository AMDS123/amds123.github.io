---
layout: post
title: "A deep learning approach for understanding natural language commands for mobile service robots"
date: 2018-07-09 11:34:21
categories: arXiv_CL
tags: arXiv_CL Attention Embedding RNN Deep_Learning Detection
author: Pedro Henrique Martins, Lu&#xed;s Cust&#xf3;dio, Rodrigo Ventura
mathjax: true
---

* content
{:toc}

##### Abstract
Using natural language to give instructions to robots is challenging, since natural language understanding is still largely an open problem. In this paper we address this problem by restricting our attention to commands modeled as one action, plus arguments (also known as slots). For action detection (also called intent detection) and slot filling various architectures of Recurrent Neural Networks and Long Short Term Memory (LSTM) networks were evaluated, having LSTMs achieved a superior accuracy. As the action requested may not fall within the robots capabilities, a Support Vector Machine(SVM) is used to determine whether it is or not. For the input of the neural networks, several word embedding algorithms were compared. Finally, to implement the system in a robot, a ROS package is created using a SMACH state machine. The proposed system is then evaluated both using well-known datasets and benchmarks in the context of domestic service robots.

##### Abstract (translated by Google)
使用自然语言向机器人发出指令具有挑战性，因为自然语言理解仍然是一个悬而未决的问题。在本文中，我们通过将注意力限制为建模为一个动作的命令以及参数（也称为插槽）来解决此问题。对于动作检测（也称为意图检测）和槽填充，评估了回归神经网络和长短期记忆（LSTM）网络的各种体系结构，使LSTM实现了高精度。由于所请求的操作可能不属于机器人功能，因此使用支持向量机（SVM）来确定它是否是。对于神经网络的输入，比较了几种字嵌入算法。最后，为了在机器人中实现该系统，使用SMACH状态机创建ROS包。然后，在家庭服务机器人的背景下，使用众所周知的数据集和基准来评估所提出的系统。

##### URL
[http://arxiv.org/abs/1807.03053](http://arxiv.org/abs/1807.03053)

##### PDF
[http://arxiv.org/pdf/1807.03053](http://arxiv.org/pdf/1807.03053)

