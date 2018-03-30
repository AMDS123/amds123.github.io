---
layout: post
title: "Speech2Vec: A Sequence-to-Sequence Framework for Learning Word Embeddings from Speech"
date: 2018-03-23 20:59:09
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model
author: Yu-An Chung, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel deep neural network architecture, Speech2Vec, for learning fixed-length vector representations of audio segments excised from a speech corpus, where the vectors contain semantic information pertaining to the underlying spoken words, and are close to other vectors in the embedding space if their corresponding underlying spoken words are semantically similar. The proposed model can be viewed as a speech version of Word2Vec. Its design is based on a RNN Encoder-Decoder framework, and borrows the methodology of skipgrams or continuous bag-of-words for training. Learning word embeddings directly from speech enables Speech2Vec to make use of the semantic information carried by speech that does not exist in plain text. The learned word embeddings are evaluated and analyzed on 13 widely used word similarity benchmarks, and outperform word embeddings learned by Word2Vec from the transcriptions.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的深度神经网络体系结构Speech2Vec，用于学习从语音语料库中删除的音频片段的固定长度向量表示，其中向量包含与基础口语词相关的语义信息，并且接近于其他向量在嵌入空间中，如果它们对应的基础口语单词在语义上相似。所提出的模型可以被视为Word2Vec的语音版本。它的设计基于一个RNN编码器 - 解码器框架，并借鉴了skipgrams的方法或用于培训的连续词汇。直接从语音中学习单词嵌入使Speech2Vec能够利用由纯文本中不存在的语音携带的语义信息。学习的词嵌入在13个广泛使用的词相似性基准上进行评估和分析，并且胜过由Word2Vec从转录中学习的词嵌入。

##### URL
[https://arxiv.org/abs/1803.08976](https://arxiv.org/abs/1803.08976)

##### PDF
[https://arxiv.org/pdf/1803.08976](https://arxiv.org/pdf/1803.08976)

