---
layout: post
title: "Learned in Translation: Contextualized Word Vectors"
date: 2018-06-20 13:15:06
categories: arXiv_AI
tags: arXiv_AI Sentiment Attention RNN Classification
author: Bryan McCann, James Bradbury, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision has benefited from initializing multiple deep layers with weights pretrained on large supervised training sets like ImageNet. Natural language processing (NLP) typically sees initialization of only the lowest layer of deep models with pretrained word vectors. In this paper, we use a deep LSTM encoder from an attentional sequence-to-sequence model trained for machine translation (MT) to contextualize word vectors. We show that adding these context vectors (CoVe) improves performance over using only unsupervised word and character vectors on a wide variety of common NLP tasks: sentiment analysis (SST, IMDb), question classification (TREC), entailment (SNLI), and question answering (SQuAD). For fine-grained sentiment analysis and entailment, CoVe improves performance of our baseline models to the state of the art.

##### Abstract (translated by Google)
计算机视觉受益于初始化多个深层图像，并在像ImageNet这样的大型监督训练集上预先加权。自然语言处理（NLP）通常只能用预训练词向量初始化深层模型的最底层。在本文中，我们使用来自机器翻译（MT）训练的注意序列到序列模型的深层LSTM编码器来上下文化词向量。我们表明，添加这些上下文向量（CoVe）可以提高性能，而不仅仅是在各种常见NLP任务中使用无监督词和字符向量：情感分析（SST，IMDb），问题分类（TREC），蕴涵（SNLI）和问题回答（SQUAD）。为了进行细粒度的情感分析和评估，CoVe将我们的基准模型的性能提高到了最先进的水平。

##### URL
[http://arxiv.org/abs/1708.00107](http://arxiv.org/abs/1708.00107)

##### PDF
[http://arxiv.org/pdf/1708.00107](http://arxiv.org/pdf/1708.00107)

