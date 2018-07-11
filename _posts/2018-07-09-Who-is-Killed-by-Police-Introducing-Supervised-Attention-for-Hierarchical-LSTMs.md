---
layout: post
title: "Who is Killed by Police: Introducing Supervised Attention for Hierarchical LSTMs"
date: 2018-07-09 22:28:09
categories: arXiv_CL
tags: arXiv_CL Attention RNN Deep_Learning Detection Recognition
author: Minh Nguyen, Thien Huu Nguyen
mathjax: true
---

* content
{:toc}

##### Abstract
Finding names of people killed by police has become increasingly important as police shootings get more and more public attention (police killing detection). Unfortunately, there has been not much work in the literature addressing this problem. The early work in this field \cite{keith2017identifying} proposed a distant supervision framework based on Expectation Maximization (EM) to deal with the multiple appearances of the names in documents. However, such EM-based framework cannot take full advantages of deep learning models, necessitating the use of hand-designed features to improve the detection performance. In this work, we present a novel deep learning method to solve the problem of police killing recognition. The proposed method relies on hierarchical LSTMs to model the multiple sentences that contain the person names of interests, and introduce supervised attention mechanisms based on semantical word lists and dependency trees to upweight the important contextual words. Our experiments demonstrate the benefits of the proposed model and yield the state-of-the-art performance for police killing detection.

##### Abstract (translated by Google)
随着警方枪击事件引起越来越多的公众关注（警方查杀），寻找被警方杀害的人的姓名变得越来越重要。不幸的是，文献中没有太多工作来解决这个问题。该领域的早期工作\ cite {keith2017identifying}提出了一个基于期望最大化（EM）的远程监督框架来处理文档中名称的多次出现。然而，这种基于EM的框架不能充分利用深度学习模型，需要使用手工设计的特征来提高检测性能。在这项工作中，我们提出了一种新的深度学习方法来解决警察杀人识别问题。所提出的方法依赖于分层LSTM来模拟包含兴趣人名的多个句子，并且引入基于语义词列表和依赖树的监督注意机制来增加重要的上下文词。我们的实验证明了所提出的模型的好处，并为警察杀人检测提供了最先进的性能。

##### URL
[http://arxiv.org/abs/1807.03409](http://arxiv.org/abs/1807.03409)

##### PDF
[http://arxiv.org/pdf/1807.03409](http://arxiv.org/pdf/1807.03409)

