---
layout: post
title: "An Encoder-Decoder Framework Translating Natural Language to Database Queries"
date: 2018-06-09 07:38:27
categories: arXiv_CL
tags: arXiv_CL CNN RNN Deep_Learning Relation
author: Ruichu Cai, Boyan Xu, Xiaoyan Yang, Zhenjie Zhang, Zijian Li, Zhihao Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Machine translation is going through a radical revolution, driven by the explosive development of deep learning techniques using Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN). In this paper, we consider a special case in machine translation problems, targeting to convert natural language into Structured Query Language (SQL) for data retrieval over relational database. Although generic CNN and RNN learn the grammar structure of SQL when trained with sufficient samples, the accuracy and training efficiency of the model could be dramatically improved, when the translation model is deeply integrated with the grammar rules of SQL. We present a new encoder-decoder framework, with a suite of new approaches, including new semantic features fed into the encoder, grammar-aware states injected into the memory of decoder, as well as recursive state management for sub-queries. These techniques help the neural network better focus on understanding semantics of operations in natural language and save the efforts on SQL grammar learning. The empirical evaluation on real world database and queries show that our approach outperform state-of-the-art solution by a significant margin.

##### Abstract (translated by Google)
借助卷积神经网络（CNN）和递归神经网络（RNN）的深度学习技术的爆炸式发展，机器翻译正在经历一场激进的革命。在本文中，我们考虑机器翻译问题中的一个特例，其目标是将自然语言转换为结构化查询语言（SQL），以便通过关系数据库进行数据检索。虽然通用的CNN和RNN在用足够的样本进行训练时学习了SQL的语法结构，但是当翻译模型与SQL的语法规则深入整合时，模型的准确性和训练效率可以得到显着提高。我们提出了一种新的编码器 - 解码器框架和一套新的方法，包括馈入编码器的新语义特征，注入解码器存储器的语法感知状态以及子查询的递归状态管理。这些技术有助于神经网络更好地关注自然语言操作的语义理解，并节省SQL语法学习的工作量。对现实世界数据库和查询的实证评估表明，我们的方法比现有技术的解决方案有显着的优势。

##### URL
[http://arxiv.org/abs/1711.06061](http://arxiv.org/abs/1711.06061)

##### PDF
[http://arxiv.org/pdf/1711.06061](http://arxiv.org/pdf/1711.06061)

