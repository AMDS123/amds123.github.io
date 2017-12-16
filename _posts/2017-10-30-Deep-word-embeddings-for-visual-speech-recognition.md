---
layout: post
title: "Deep word embeddings for visual speech recognition"
date: 2017-10-30 19:09:29
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Embedding CNN RNN Deep_Learning Recognition
author: Themos Stafylakis, Georgios Tzimiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a deep learning architecture for extracting word embeddings for visual speech recognition. The embeddings summarize the information of the mouth region that is relevant to the problem of word recognition, while suppressing other types of variability such as speaker, pose and illumination. The system is comprised of a spatiotemporal convolutional layer, a Residual Network and bidirectional LSTMs and is trained on the Lipreading in-the-wild database. We first show that the proposed architecture goes beyond state-of-the-art on closed-set word identification, by attaining 11.92% error rate on a vocabulary of 500 words. We then examine the capacity of the embeddings in modelling words unseen during training. We deploy Probabilistic Linear Discriminant Analysis (PLDA) to model the embeddings and perform low-shot learning experiments on words unseen during training. The experiments demonstrate that word-level visual speech recognition is feasible even in cases where the target words are not included in the training set.

##### Abstract (translated by Google)
在本文中，我们提出了一个深度学习的体系结构来提取词语嵌入视觉语音识别。这些嵌入概括了与词汇识别问题相关的嘴部区域的信息，同时抑制了其他类型的变化，如说话人，姿势和照明。该系统由时空卷积层，残余网络和双向LSTM构成，并在Lipread野外数据库中进行培训。我们首先表明，所提出的体系结构超越了封闭式词语识别的最新水平，在500字的词汇量上达到了11.92％的错误率。然后，我们研究在训练期间看不到的嵌入的能力。我们使用概率线性判别分析（PLDA）来对嵌入进行建模，并对训练期间看不见的单词进行低级学习实验。实验表明，即使在目标词不包含在训练集中的情况下，词级视觉语音识别也是可行的。

##### URL
[https://arxiv.org/abs/1710.11201](https://arxiv.org/abs/1710.11201)

##### PDF
[https://arxiv.org/pdf/1710.11201](https://arxiv.org/pdf/1710.11201)

