---
layout: post
title: "Interpretation of Semantic Tweet Representations"
date: 2017-06-21 06:59:17
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding Represenation_Learning RNN Prediction
author: J Ganesh, Manish Gupta, Vasudeva Varma
mathjax: true
---

* content
{:toc}

##### Abstract
Research in analysis of microblogging platforms is experiencing a renewed surge with a large number of works applying representation learning models for applications like sentiment analysis, semantic textual similarity computation, hashtag prediction, etc. Although the performance of the representation learning models has been better than the traditional baselines for such tasks, little is known about the elementary properties of a tweet encoded within these representations, or why particular representations work better for certain tasks. Our work presented here constitutes the first step in opening the black-box of vector embeddings for tweets. Traditional feature engineering methods for high-level applications have exploited various elementary properties of tweets. We believe that a tweet representation is effective for an application because it meticulously encodes the application-specific elementary properties of tweets. To understand the elementary properties encoded in a tweet representation, we evaluate the representations on the accuracy to which they can model each of those properties such as tweet length, presence of particular words, hashtags, mentions, capitalization, etc. Our systematic extensive study of nine supervised and four unsupervised tweet representations against most popular eight textual and five social elementary properties reveal that Bi-directional LSTMs (BLSTMs) and Skip-Thought Vectors (STV) best encode the textual and social properties of tweets respectively. FastText is the best model for low resource settings, providing very little degradation with reduction in embedding size. Finally, we draw interesting insights by correlating the model performance obtained for elementary property prediction tasks with the highlevel downstream applications.

##### Abstract (translated by Google)
微博平台的分析研究正在经历一个新的浪潮，大量的应用表情学习模型的应用，如情感分析，语义相似度计算，标签预测等，虽然表现学习模型的性能比这些任务的传统基线，对于在这些表示中编码的鸣叫的基本属性知之甚少，或者为什么特定的表示对某些任务更好地工作。我们在这里介绍的工作构成了打开微博向量嵌入黑盒子的第一步。针对高级应用程序的传统特征工程方法已经利用了推文的各种基本属性。我们认为，鸣叫表示对于应用程序是有效的，因为它精确地编码了鸣叫的特定于应用程序的基本属性。为了理解在推特表示中编码的基本属性，我们评估了他们可以对这些属性进行建模的准确性的表示，例如推特长度，特定词的存在，主题标签，提及，大小写等。对最流行的八个文本和五个社会基本属性的九个受监督的和四个无监督的鸣叫表示显示双向LSTM（BLSTM）和跳跃思想向量（STV）分别对推文的文本和社会属性进行最佳编码。 FastText是低资源设置的最佳模式，可减少嵌入大小，从而提供极少的降级。最后，我们通过将基本属性预测任务所获得的模型性能与高层次的下游应用程序相关联来绘制有趣的见解。

##### URL
[https://arxiv.org/abs/1704.00898](https://arxiv.org/abs/1704.00898)

##### PDF
[https://arxiv.org/pdf/1704.00898](https://arxiv.org/pdf/1704.00898)

