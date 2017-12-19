---
layout: post
title: "Jointly Modeling Embedding and Translation to Bridge Video and Language"
date: 2015-06-04 07:17:06
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN RNN Relation
author: Yingwei Pan, Tao Mei, Ting Yao, Houqiang Li, Yong Rui
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically describing video content with natural language is a fundamental challenge of multimedia. Recurrent Neural Networks (RNN), which models sequence dynamics, has attracted increasing attention on visual interpretation. However, most existing approaches generate a word locally with given previous words and the visual content, while the relationship between sentence semantics and visual content is not holistically exploited. As a result, the generated sentences may be contextually correct but the semantics (e.g., subjects, verbs or objects) are not true. This paper presents a novel unified framework, named Long Short-Term Memory with visual-semantic Embedding (LSTM-E), which can simultaneously explore the learning of LSTM and visual-semantic embedding. The former aims to locally maximize the probability of generating the next word given previous words and visual content, while the latter is to create a visual-semantic embedding space for enforcing the relationship between the semantics of the entire sentence and visual content. Our proposed LSTM-E consists of three components: a 2-D and/or 3-D deep convolutional neural networks for learning powerful video representation, a deep RNN for generating sentences, and a joint embedding model for exploring the relationships between visual content and sentence semantics. The experiments on YouTube2Text dataset show that our proposed LSTM-E achieves to-date the best reported performance in generating natural sentences: 45.3% and 31.0% in terms of BLEU@4 and METEOR, respectively. We also demonstrate that LSTM-E is superior in predicting Subject-Verb-Object (SVO) triplets to several state-of-the-art techniques.

##### Abstract (translated by Google)
用自然语言自动描述视频内容是多媒体的基本挑战。递归神经网络（RNN）模拟序列动力学，在视觉解释上引起越来越多的关注。然而，大多数现有的方法在给定的前一个词和视觉内容的地方产生一个词，而句子语义和视觉内容之间的关系并没有被整体地利用。结果，所生成的句子可以是上下文正确的，但是语义（例如主语，动词或宾语）不是真的。本文提出了一种新的统一框架，即视觉语义嵌入的长时间短记忆（LSTM-E），它可以同时探索LSTM的学习和视觉语义嵌入。前者旨在局部最大化产生下一个词的概率，给出前一个词和视觉内容，而后者则是创建一个视觉语义嵌入空间，用于强化整个句子的语义与视觉内容之间的关系。我们提出的LSTM-E由三部分组成：用于学习强大的视频表示的二维和/或三维深度卷积神经网络，用于生成句子的深度RNN以及用于探索视觉内容和句子语义。在YouTube2Text数据集上的实验表明，我们提出的LSTM-E在BLEU4和METEOR方面取得了最好的报告性能，分别为45.3％和31.0％。我们还证明，LSTM-E在预测主体 - 动词 - 对象（SVO）三元组方面优于几种最先进的技术。

##### URL
[https://arxiv.org/abs/1505.01861](https://arxiv.org/abs/1505.01861)

##### PDF
[https://arxiv.org/pdf/1505.01861](https://arxiv.org/pdf/1505.01861)

