---
layout: post
title: "Character-level Deep Conflation for Business Data Analytics"
date: 2017-02-08 22:24:14
categories: arXiv_SD
tags: arXiv_SD CNN RNN Gradient_Descent
author: Zhe Gan, P. D. Singh, Ameet Joshi, Xiaodong He, Jianshu Chen, Jianfeng Gao, Li Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Connecting different text attributes associated with the same entity (conflation) is important in business data analytics since it could help merge two different tables in a database to provide a more comprehensive profile of an entity. However, the conflation task is challenging because two text strings that describe the same entity could be quite different from each other for reasons such as misspelling. It is therefore critical to develop a conflation model that is able to truly understand the semantic meaning of the strings and match them at the semantic level. To this end, we develop a character-level deep conflation model that encodes the input text strings from character level into finite dimension feature vectors, which are then used to compute the cosine similarity between the text strings. The model is trained in an end-to-end manner using back propagation and stochastic gradient descent to maximize the likelihood of the correct association. Specifically, we propose two variants of the deep conflation model, based on long-short-term memory (LSTM) recurrent neural network (RNN) and convolutional neural network (CNN), respectively. Both models perform well on a real-world business analytics dataset and significantly outperform the baseline bag-of-character (BoC) model.

##### Abstract (translated by Google)
连接与相同实体关联的不同文本属性（合并）在业务数据分析中非常重要，因为它可以帮助合并数据库中的两个不同表格，以提供更全面的实体配置文件。然而，合并任务是具有挑战性的，因为描述相同实体的两个文本字符串由于拼写错误等原因可能彼此不同。因此，开发一种能够真正理解字符串的语义并在语义层面上匹配的合作模型是至关重要的。为此，我们开发了一个字符级深度合并模型，将输入文本字符串从字符级别编码为有限维度特征向量，然后用于计算文本字符串之间的余弦相似度。该模型以端对端的方式使用反向传播和随机梯度下降进行训练，以最大化正确关联的可能性。具体而言，我们分别基于长期短期记忆（LSTM）递归神经网络（RNN）和卷积神经网络（CNN）提出了两种深度合并模型的变体。这两种模型在真实世界的业务分析数据集上表现都很好，并且明显优于基准袋特性（BoC）模型。

##### URL
[https://arxiv.org/abs/1702.02640](https://arxiv.org/abs/1702.02640)

##### PDF
[https://arxiv.org/pdf/1702.02640](https://arxiv.org/pdf/1702.02640)

