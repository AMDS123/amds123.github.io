---
layout: post
title: "Segmental Audio Word2Vec: Representing Utterances as Sequences of Vectors with Applications in Spoken Term Detection"
date: 2018-08-07 06:47:50
categories: arXiv_CL
tags: arXiv_CL Segmentation Reinforcement_Learning Language_Model Detection
author: Yu-Hsuan Wang, Hung-yi Lee, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
While Word2Vec represents words (in text) as vectors carrying semantic information, audio Word2Vec was shown to be able to represent signal segments of spoken words as vectors carrying phonetic structure information. Audio Word2Vec can be trained in an unsupervised way from an unlabeled corpus, except the word boundaries are needed. In this paper, we extend audio Word2Vec from word-level to utterance-level by proposing a new segmental audio Word2Vec, in which unsupervised spoken word boundary segmentation and audio Word2Vec are jointly learned and mutually enhanced, so an utterance can be directly represented as a sequence of vectors carrying phonetic structure information. This is achieved by a segmental sequence-to-sequence autoencoder (SSAE), in which a segmentation gate trained with reinforcement learning is inserted in the encoder. Experiments on English, Czech, French and German show very good performance in both unsupervised spoken word segmentation and spoken term detection applications (significantly better than frame-based DTW).

##### Abstract (translated by Google)
虽然Word2Vec将单词（在文本中）表示为携带语义信息的向量，但是音频Word2Vec被示出能够将口语单词的信号段表示为携带语音结构信息的向量。音频Word2Vec可以从未标记的语料库中以无人监督的方式进行训练，除了需要单词边界。在本文中，我们通过提出一个新的分段音频Word2Vec将音频Word2Vec从单词级扩展到话语级，其中无监督口语词边界分割和音频Word2Vec被联合学习和相互增强，因此话语可以直接表示为携带语音结构信息的载体序列。这是通过分段序列到序列自动编码器（SSAE）来实现的，其中在编码器中插入用强化学习训练的分段门。英语，捷克语，法语和德语的实验在无人监督的口语分词和口语术语检测应用中都表现出非常好的表现（明显优于基于帧的DTW）。

##### URL
[http://arxiv.org/abs/1808.02228](http://arxiv.org/abs/1808.02228)

##### PDF
[http://arxiv.org/pdf/1808.02228](http://arxiv.org/pdf/1808.02228)

