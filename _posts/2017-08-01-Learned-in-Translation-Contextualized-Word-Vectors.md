---
layout: post
title: "Learned in Translation: Contextualized Word Vectors"
date: 2017-08-01 00:05:34
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention RNN Classification
author: Bryan McCann, James Bradbury, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision has benefited from initializing multiple deep layers with weights pretrained on large supervised training sets like ImageNet. Natural language processing (NLP) typically sees initialization of only the lowest layer of deep models with pretrained word vectors. In this paper, we use a deep LSTM encoder from an attentional sequence-to-sequence model trained for machine translation (MT) to contextualize word vectors. We show that adding these context vectors (CoVe) improves performance over using only unsupervised word and character vectors on a wide variety of common NLP tasks: sentiment analysis (SST, IMDb), question classification (TREC), entailment (SNLI), and question answering (SQuAD). For fine-grained sentiment analysis and entailment, CoVe improves performance of our baseline models to the state of the art.

##### Abstract (translated by Google)
计算机视觉已经从初始化多个深层，利用在像ImageNet这样的大型监督训练集上预先训练的权重获益。自然语言处理（NLP）通常只能用预训练词向量初始化深层模型的最底层。在本文中，我们使用从机器翻译（MT）训练的注意序列到序列模型的深度LSTM编码器来上下文化词向量。我们证明，添加这些上下文向量（CoVe）可以提高性能，而不仅仅是使用无监督的单词和字符向量来处理各种常见的NLP任务：情感分析（SST，IMDb），问题分类（TREC），蕴涵（SNLI）和问题回答（SQUAD）。为了进行细粒度的情感分析和评估，CoVe将我们的基准模型的性能提升到了最先进的水平。

##### URL
[https://arxiv.org/abs/1708.00107](https://arxiv.org/abs/1708.00107)

##### PDF
[https://arxiv.org/pdf/1708.00107](https://arxiv.org/pdf/1708.00107)

