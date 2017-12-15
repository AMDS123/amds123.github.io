---
layout: post
title: "Aspect-based Opinion Summarization with Convolutional Neural Networks"
date: 2015-11-30 01:46:15
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Sentiment_Classification Summarization Embedding CNN Classification
author: Haibing Wu, Yiwei Gu, Shangdi Sun, Xiaodong Gu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers Aspect-based Opinion Summarization (AOS) of reviews on particular products. To enable real applications, an AOS system needs to address two core subtasks, aspect extraction and sentiment classification. Most existing approaches to aspect extraction, which use linguistic analysis or topic modeling, are general across different products but not precise enough or suitable for particular products. Instead we take a less general but more precise scheme, directly mapping each review sentence into pre-defined aspects. To tackle aspect mapping and sentiment classification, we propose two Convolutional Neural Network (CNN) based methods, cascaded CNN and multitask CNN. Cascaded CNN contains two levels of convolutional networks. Multiple CNNs at level 1 deal with aspect mapping task, and a single CNN at level 2 deals with sentiment classification. Multitask CNN also contains multiple aspect CNNs and a sentiment CNN, but different networks share the same word embeddings. Experimental results indicate that both cascaded and multitask CNNs outperform SVM-based methods by large margins. Multitask CNN generally performs better than cascaded CNN.

##### Abstract (translated by Google)
本文考虑了对特定产品评论的基于方面的意见摘要（AOS）。为了实现真正的应用，AOS系统需要解决两个核心子任务，方面提取和情感分类。大多数现有的使用语言分析或主题建模的方面提取方法在不同的产品中是普遍的，但是不够精确或不适合于特定的产品。相反，我们采取一个不太一般但更精确的方案，将每个评论语句直接映射到预定义的方面。为了处理方面的映射和情感分类，我们提出了两种基于卷积神经网络（CNN）的方法，CNN级联和多任务CNN。级联的CNN包含两级卷积网络。 1级的多个CNN处理方面映射任务，2级单个CNN处理情感分类。多任务CNN也包含多个方面的CNN和情绪CNN，但不同的网络共享相同的单词嵌入。实验结果表明，级联和多任务CNN的性能都优于基于SVM的方法。多任务CNN通常表现优于级联CNN。

##### URL
[https://arxiv.org/abs/1511.09128](https://arxiv.org/abs/1511.09128)

##### PDF
[https://arxiv.org/pdf/1511.09128](https://arxiv.org/pdf/1511.09128)

