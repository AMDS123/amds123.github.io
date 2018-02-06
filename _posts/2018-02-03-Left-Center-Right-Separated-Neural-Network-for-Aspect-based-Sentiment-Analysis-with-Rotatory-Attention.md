---
layout: post
title: "Left-Center-Right Separated Neural Network for Aspect-based Sentiment Analysis with Rotatory Attention"
date: 2018-02-03 01:43:37
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Attention RNN Deep_Learning Relation
author: Shiliang Zheng, Rui Xia
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques have achieved success in aspect-based sentiment analysis in recent years. However, there are two important issues that still remain to be further studied, i.e., 1) how to efficiently represent the target especially when the target contains multiple words; 2) how to utilize the interaction between target and left/right contexts to capture the most important words in them. In this paper, we propose an approach, called left-center-right separated neural network with rotatory attention (LCR-Rot), to better address the two problems. Our approach has two characteristics: 1) it has three separated LSTMs, i.e., left, center and right LSTMs, corresponding to three parts of a review (left context, target phrase and right context); 2) it has a rotatory attention mechanism which models the relation between target and left/right contexts. The target2context attention is used to capture the most indicative sentiment words in left/right contexts. Subsequently, the context2target attention is used to capture the most important word in the target. This leads to a two-side representation of the target: left-aware target and right-aware target. We compare our approach on three benchmark datasets with ten related methods proposed recently. The results show that our approach significantly outperforms the state-of-the-art techniques.

##### Abstract (translated by Google)
深度学习技术近年来在基于方面的情感分析方面取得了成功。然而，还有两个重要问题还有待进一步研究，即：1）如何有效地表达目标，特别是当目标包含多个单词时; 2）如何利用目标与左/右上下文之间的交互来捕捉其中最重要的单词。在本文中，我们提出了一种被称为左旋中心分离神经网络（LCR-Rot）的方法来更好地解决这两个问题。我们的方法有两个特点：1）它有三个分离的LSTM，即左，中，右LSTM，对应于评论的三个部分（左上下文，目标短语和右上下文）; 2）它有一个旋转的注意机制，模拟目标和左/右上下文之间的关系。 target2context注意被用来捕获左/右上下文中最具指示性的情感词汇。随后，context2target注意被用来捕捉目标中最重要的单词。这导致目标的双向表示：左感知目标和右感知目标。我们将三种基准数据集的方法与最近提出的十种相关方法进行比较。结果表明，我们的方法明显优于最先进的技术。

##### URL
[http://arxiv.org/abs/1802.00892](http://arxiv.org/abs/1802.00892)

##### PDF
[http://arxiv.org/pdf/1802.00892](http://arxiv.org/pdf/1802.00892)

