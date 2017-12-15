---
layout: post
title: "An Empirical Exploration of Skip Connections for Sequential Tagging"
date: 2016-10-11 03:02:38
categories: arXiv_CL
tags: arXiv_CL RNN
author: Huijia Wu, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we empirically explore the effects of various kinds of skip connections in stacked bidirectional LSTMs for sequential tagging. We investigate three kinds of skip connections connecting to LSTM cells: (a) skip connections to the gates, (b) skip connections to the internal states and (c) skip connections to the cell outputs. We present comprehensive experiments showing that skip connections to cell outputs outperform the remaining two. Furthermore, we observe that using gated identity functions as skip mappings works pretty well. Based on this novel skip connections, we successfully train deep stacked bidirectional LSTM models and obtain state-of-the-art results on CCG supertagging and comparable results on POS tagging.

##### Abstract (translated by Google)
在本文中，我们通过实验探索了堆栈双向LSTM中的各种跳跃连接对顺序标记的影响。我们调查连接到LSTM单元的三种跳转连接：（a）跳过连接到门，（b）跳过到内部状态的连接，（c）跳过连接到单元输出。我们目前的综合实验显示跳转到单元输出的连接优于其余两个。此外，我们观察到，使用门控身份函数作为跳过映射工作得很好。基于这种新颖的跳过连接，我们成功地训练深层堆叠双向LSTM模型，并获得CCG超级标签上的最新结果以及POS标签上的可比结果。

##### URL
[https://arxiv.org/abs/1610.03167](https://arxiv.org/abs/1610.03167)

##### PDF
[https://arxiv.org/pdf/1610.03167](https://arxiv.org/pdf/1610.03167)

