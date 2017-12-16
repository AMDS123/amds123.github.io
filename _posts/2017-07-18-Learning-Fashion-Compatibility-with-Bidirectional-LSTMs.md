---
layout: post
title: "Learning Fashion Compatibility with Bidirectional LSTMs"
date: 2017-07-18 15:36:53
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding RNN Quantitative Relation Recommendation
author: Xintong Han, Zuxuan Wu, Yu-Gang Jiang, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
The ubiquity of online fashion shopping demands effective recommendation services for customers. In this paper, we study two types of fashion recommendation: (i) suggesting an item that matches existing components in a set to form a stylish outfit (a collection of fashion items), and (ii) generating an outfit with multimodal (images/text) specifications from a user. To this end, we propose to jointly learn a visual-semantic embedding and the compatibility relationships among fashion items in an end-to-end fashion. More specifically, we consider a fashion outfit to be a sequence (usually from top to bottom and then accessories) and each item in the outfit as a time step. Given the fashion items in an outfit, we train a bidirectional LSTM (Bi-LSTM) model to sequentially predict the next item conditioned on previous ones to learn their compatibility relationships. Further, we learn a visual-semantic space by regressing image features to their semantic representations aiming to inject attribute and category information as a regularization for training the LSTM. The trained network can not only perform the aforementioned recommendations effectively but also predict the compatibility of a given outfit. We conduct extensive experiments on our newly collected Polyvore dataset, and the results provide strong qualitative and quantitative evidence that our framework outperforms alternative methods.

##### Abstract (translated by Google)
网上时尚购物的无处不在为客户提供有效的推荐服务。在本文中，我们研究了两种类型的时尚推荐：（i）提出一个项目，以匹配集合中的现有组件来形成一个时尚的服装（一系列时尚物品），和（ii）用多模式（图像/文本）来自用户的规范。为此，我们建议以端到端的方式共同学习视觉语义嵌入和时尚物品之间的兼容关系。更具体地说，我们认为时装是一个序列（通常是从上到下，然后是饰品），而且每件衣服都是一个时间步骤。考虑到服装中的时尚物品，我们训练一个双向LSTM（Bi-LSTM）模型来顺序地预测下一个项目，以了解它们之间的兼容性关系。此外，我们通过将图像特征回归到它们的语义表示来学习一个视觉 - 语义空间，旨在注入属性和类别信息作为训练LSTM的正则化。训练好的网络不仅可以有效地执行上述建议，还可以预测给定服装的兼容性。我们对新收集的Polyvore数据集进行了广泛的实验，结果提供了强有力的定性和定量证据，表明我们的框架优于其他方法。

##### URL
[https://arxiv.org/abs/1707.05691](https://arxiv.org/abs/1707.05691)

##### PDF
[https://arxiv.org/pdf/1707.05691](https://arxiv.org/pdf/1707.05691)

