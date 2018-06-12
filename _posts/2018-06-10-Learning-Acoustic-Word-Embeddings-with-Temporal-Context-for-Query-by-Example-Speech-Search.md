---
layout: post
title: "Learning Acoustic Word Embeddings with Temporal Context for Query-by-Example Speech Search"
date: 2018-06-10 09:40:08
categories: arXiv_CL
tags: arXiv_CL Embedding CNN
author: Yougen Yuan, Cheung-Chi Leung, Lei Xie, Hongjie Chen, Bin Ma, Haizhou Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to learn acoustic word embeddings with temporal context for query-by-example (QbE) speech search. The temporal context includes the leading and trailing word sequences of a word. We assume that there exist spoken word pairs in the training database. We pad the word pairs with their original temporal context to form fixed-length speech segment pairs. We obtain the acoustic word embeddings through a deep convolutional neural network (CNN) which is trained on the speech segment pairs with a triplet loss. Shifting a fixed-length analysis window through the search content, we obtain a running sequence of embeddings. In this way, searching for the spoken query is equivalent to the matching of acoustic word embeddings. The experiments show that our proposed acoustic word embeddings learned with temporal context are effective in QbE speech search. They outperform the state-of-the-art frame-level feature representations and reduce run-time computation since no dynamic time warping is required in QbE speech search. We also find that it is important to have sufficient speech segment pairs to train the deep CNN for effective acoustic word embeddings.

##### Abstract (translated by Google)
我们建议学习具有时间上下文的声学词嵌入以用于例如查询（QbE）语音搜索。时间上下文包括单词的前导和后续单词序列。我们假设训练数据库中存在口语词对。我们使用它们的原始时间上下文来填充单词对以形成固定长度的语音片段对。我们通过深度卷积神经网络（CNN）获得声学词汇嵌入，该网络在语音片段对上受到三重损失的训练。通过搜索内容移动一个固定长度的分析窗口，我们获得一个正在运行的嵌入序列。这样，搜索口头查询就相当于声音词嵌入的匹配。实验表明，我们提出的用时间上下文学习的声学词嵌入在QbE语音搜索中是有效的。它们优于最先进的帧级特征表示，并且减少了运行时间计算，因为在QbE语音搜索中不需要动态时间扭曲。我们还发现，重要的是要有足够的语音段对来训练深度CNN以获得有效的声学字嵌入。

##### URL
[http://arxiv.org/abs/1806.03621](http://arxiv.org/abs/1806.03621)

##### PDF
[http://arxiv.org/pdf/1806.03621](http://arxiv.org/pdf/1806.03621)

