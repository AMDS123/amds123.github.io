---
layout: post
title: "Learning to Skim Text"
date: 2017-04-29 19:58:31
categories: arXiv_CL
tags: arXiv_CL Sentiment RNN Classification Prediction
author: Adams Wei Yu, Hongrae Lee, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks are showing much promise in many sub-areas of natural language processing, ranging from document classification to machine translation to automatic question answering. Despite their promise, many recurrent models have to read the whole text word by word, making it slow to handle long documents. For example, it is difficult to use a recurrent network to read a book and answer questions about it. In this paper, we present an approach of reading text while skipping irrelevant information if needed. The underlying model is a recurrent network that learns how far to jump after reading a few words of the input text. We employ a standard policy gradient method to train the model to make discrete jumping decisions. In our benchmarks on four different tasks, including number prediction, sentiment analysis, news article classification and automatic Q\&A, our proposed model, a modified LSTM with jumping, is up to 6 times faster than the standard sequential LSTM, while maintaining the same or even better accuracy.

##### Abstract (translated by Google)
递归神经网络在自然语言处理的许多子领域显示出很大的前景，从文档分类到机器翻译到自动问答。尽管他们承诺，许多复发的模型必须逐字阅读全文，使得处理长文件变得缓慢。例如，用一个经常性的网络来阅读一本书并回答关于它的问题是很困难的。在本文中，我们提出了阅读文本的方法，如果需要跳过不相关的信息。基础模型是一个经常性的网络，通过阅读输入文本的几个词汇，学习跳转到什么程度。我们采用标准的策略梯度方法来训练模型以做出不连续的跳跃决策。在包括数量预测，情感分析，新闻文章分类和自动Q \ A这四个不同任务的基准测试中，我们提出的带有跳跃的改进型LSTM模型比标准顺序LSTM快6倍，同时保持相同甚至更好的准确性。

##### URL
[https://arxiv.org/abs/1704.06877](https://arxiv.org/abs/1704.06877)

##### PDF
[https://arxiv.org/pdf/1704.06877](https://arxiv.org/pdf/1704.06877)

