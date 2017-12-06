---
layout: post
title: "Deep Recurrent Models with Fast-Forward Connections for Neural Machine Translation"
date: 2016-07-23 13:14:17
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Jie Zhou, Ying Cao, Xuguang Wang, Peng Li, Wei Xu
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) aims at solving machine translation (MT) problems using neural networks and has exhibited promising results in recent years. However, most of the existing NMT models are shallow and there is still a performance gap between a single NMT model and the best conventional MT system. In this work, we introduce a new type of linear connections, named fast-forward connections, based on deep Long Short-Term Memory (LSTM) networks, and an interleaved bi-directional architecture for stacking the LSTM layers. Fast-forward connections play an essential role in propagating the gradients and building a deep topology of depth 16. On the WMT'14 English-to-French task, we achieve BLEU=37.7 with a single attention model, which outperforms the corresponding single shallow model by 6.2 BLEU points. This is the first time that a single NMT model achieves state-of-the-art performance and outperforms the best conventional model by 0.7 BLEU points. We can still achieve BLEU=36.3 even without using an attention mechanism. After special handling of unknown words and model ensembling, we obtain the best score reported to date on this task with BLEU=40.4. Our models are also validated on the more difficult WMT'14 English-to-German task.

##### Abstract (translated by Google)
神经机器翻译（NMT）旨在利用神经网络解决机器翻译（MT）问题，近年来取得了令人鼓舞的成果。然而，现有的NMT模型大部分是浅层的，单一的NMT模型和最好的常规MT系统之间仍然存在性能差距。在这项工作中，我们引入一种新型的线性连接，称为快速前向连接，基于深LSTM（Long Long Term Memory）网络，以及用于层叠LSTM层的交叉双向架构。快速连接在传播梯度和构建深度拓扑深度方面起着至关重要的作用。在WMT'14英语到法语任务中，我们使用单一注意模型实现了BLEU = 37.7，该模型优于相应的单一浅层模型由6.2 BLEU点。这是一个单一的NMT模型首次实现了最先进的性能，并且比传统的最佳模型优于0.7 BLEU点。即使不使用注意机制，我们仍然可以达到BLEU = 36.3。在对未知单词和模型集成进行特殊处理之后，我们获得了BLEU = 40.4这个任务上迄今为止报告的最好成绩。我们的模型也在更困难的WMT'14英语 - 德语任务中验证。

##### URL
[https://arxiv.org/abs/1606.04199](https://arxiv.org/abs/1606.04199)

