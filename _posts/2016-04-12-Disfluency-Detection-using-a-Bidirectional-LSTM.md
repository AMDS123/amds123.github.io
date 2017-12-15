---
layout: post
title: "Disfluency Detection using a Bidirectional LSTM"
date: 2016-04-12 02:34:00
categories: arXiv_SD
tags: arXiv_SD RNN Detection
author: Vicky Zayats, Mari Ostendorf, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new approach for disfluency detection using a Bidirectional Long-Short Term Memory neural network (BLSTM). In addition to the word sequence, the model takes as input pattern match features that were developed to reduce sensitivity to vocabulary size in training, which lead to improved performance over the word sequence alone. The BLSTM takes advantage of explicit repair states in addition to the standard reparandum states. The final output leverages integer linear programming to incorporate constraints of disfluency structure. In experiments on the Switchboard corpus, the model achieves state-of-the-art performance for both the standard disfluency detection task and the correction detection task. Analysis shows that the model has better detection of non-repetition disfluencies, which tend to be much harder to detect.

##### Abstract (translated by Google)
我们引入一种新的方法来检测使用双向长短期记忆神经网络（BLSTM）的流利度。除了单词序列之外，该模型还将输入模式匹配特征作为开发目的，以减少对训练中​​词汇量的敏感度，从而提高单词序列的性能。 BLSTM除了标准的重置状态之外还利用了明确的修复状态。最终的输出利用整数线性规划来结合不合理结构的约束。在交换机语料库的实验中，该模型实现了标准的不流畅检测任务和校正检测任务的最新性能。分析表明，该模型能够更好地检测到不重复的不良情况，而这种情况往往难以发现。

##### URL
[https://arxiv.org/abs/1604.03209](https://arxiv.org/abs/1604.03209)

##### PDF
[https://arxiv.org/pdf/1604.03209](https://arxiv.org/pdf/1604.03209)

