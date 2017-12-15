---
layout: post
title: "Wikipedia Vandal Early Detection: from User Behavior to User Embedding"
date: 2017-06-03 02:42:40
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Deep_Learning Detection
author: Shuhan Yuan, Panpan Zheng, Xintao Wu, Yang Xiang
mathjax: true
---

* content
{:toc}

##### Abstract
Wikipedia is the largest online encyclopedia that allows anyone to edit articles. In this paper, we propose the use of deep learning to detect vandals based on their edit history. In particular, we develop a multi-source long-short term memory network (M-LSTM) to model user behaviors by using a variety of user edit aspects as inputs, including the history of edit reversion information, edit page titles and categories. With M-LSTM, we can encode each user into a low dimensional real vector, called user embedding. Meanwhile, as a sequential model, M-LSTM updates the user embedding each time after the user commits a new edit. Thus, we can predict whether a user is benign or vandal dynamically based on the up-to-date user embedding. Furthermore, those user embeddings are crucial to discover collaborative vandals.

##### Abstract (translated by Google)
维基百科是最大的在线百科全书，允许任何人编辑文章。在本文中，我们提出使用深度学习来检测破坏者的编辑历史。具体来说，我们开发了一个多源长时间记忆网络（M-LSTM），通过使用各种用户编辑方面的输入，包括编辑回复信息的历史，编辑页面标题和类别，对用户行为进行建模。使用M-LSTM，我们可以将每个用户编码成一个低维实数矢量，称为用户嵌入。同时，作为一个顺序模型，M-LSTM在用户提交新的编辑之后每次更新用户嵌入。因此，我们可以基于最新的用户嵌入来预测用户是良性的还是动态的。而且，这些用户嵌入对发现协同破坏者至关重要。

##### URL
[https://arxiv.org/abs/1706.00887](https://arxiv.org/abs/1706.00887)

##### PDF
[https://arxiv.org/pdf/1706.00887](https://arxiv.org/pdf/1706.00887)

