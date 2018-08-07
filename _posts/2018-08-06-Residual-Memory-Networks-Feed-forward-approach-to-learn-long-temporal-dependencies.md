---
layout: post
title: "Residual Memory Networks: Feed-forward approach to learn long temporal dependencies"
date: 2018-08-06 14:00:40
categories: arXiv_CL
tags: arXiv_CL RNN Memory_Networks Recognition
author: Murali Karthick Baskar, Martin Karafiat, Lukas Burget, Karel Vesely, Frantisek Grezl, Jan Honza Cernocky
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep recurrent neural network (RNN) architectures is complicated due to the increased network complexity. This disrupts the learning of higher order abstracts using deep RNN. In case of feed-forward networks training deep structures is simple and faster while learning long-term temporal information is not possible. In this paper we propose a residual memory neural network (RMN) architecture to model short-time dependencies using deep feed-forward layers having residual and time delayed connections. The residual connection paves way to construct deeper networks by enabling unhindered flow of gradients and the time delay units capture temporal information with shared weights. The number of layers in RMN signifies both the hierarchical processing depth and temporal depth. The computational complexity in training RMN is significantly less when compared to deep recurrent networks. RMN is further extended as bi-directional RMN (BRMN) to capture both past and future information. Experimental analysis is done on AMI corpus to substantiate the capability of RMN in learning long-term information and hierarchical information. Recognition performance of RMN trained with 300 hours of Switchboard corpus is compared with various state-of-the-art LVCSR systems. The results indicate that RMN and BRMN gains 6 % and 3.8 % relative improvement over LSTM and BLSTM networks.

##### Abstract (translated by Google)
由于网络复杂性的增加，训练深度递归神经网络（RNN）架构很复杂。这破坏了使用深度RNN学习高阶摘要的过程。在前馈网络的情况下，训练深层结构简单且快速，同时不可能学习长期时间信息。在本文中，我们提出了一种残余记忆神经网络（RMN）架构，使用具有残余和时间延迟连接的深度前馈层来模拟短时依赖性。剩余连接通过实现无阻碍的梯度流来构建更深的网络，并且时间延迟单元利用共享权重捕获时间信息。 RMN中的层数表示分层处理深度和时间深度。与深度复现网络相比，训练RMN的计算复杂度显着降低。 RMN进一步扩展为双向RMN（BRMN）以捕获过去和未来信息。对AMI语料库进行实验分析，以证实RMN在学习长期信息和分层信息方面的能力。使用300小时的Switchboard语料库训练的RMN的识别性能与各种最先进的LVCSR系统进行比较。结果表明，与LSTM和BLSTM网络相比，RMN和BRMN相对改善了6％和3.8％。

##### URL
[http://arxiv.org/abs/1808.01916](http://arxiv.org/abs/1808.01916)

##### PDF
[http://arxiv.org/pdf/1808.01916](http://arxiv.org/pdf/1808.01916)

