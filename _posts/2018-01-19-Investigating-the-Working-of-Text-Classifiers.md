---
layout: post
title: "Investigating the Working of Text Classifiers"
date: 2018-01-19 00:29:55
categories: arXiv_CL
tags: arXiv_CL Regularization Text_Classification Classification
author: Devendra Singh Sachan, Manzil Zaheer, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Text classification is one of the most widely studied task in natural language processing. Recently, larger and larger multilayer neural network models are employed for the task motivated by the principle of compositionality. Almost all of the methods reported use discriminative approaches for the task. Discriminative approaches come with a caveat that if there is no proper capacity control, it might latch on to any signal even though it might not generalize. With use of various state-of-the-art approaches for text classifiers, we want to explore if the models actually learn to compose meaning of the sentences or still just use some key lexicons. To test our hypothesis, we construct datasets where the train and test split have no direct overlap of such lexicons. We study various text classifiers and observe that there is a big performance drop on these datasets. Finally, we show that even simple regularization techniques can improve performance on these datasets.

##### Abstract (translated by Google)
文本分类是自然语言处理中研究最为广泛的任务之一。最近，越来越多的多层神经网络模型被用于由组合性原理驱动的任务。几乎所有报告的方法都使用区分方法来完成任务。判别式方法带来的一个警告是，如果没有适当的容量控制，它可能会锁定任何信号，即使它不能一概而论。通过使用各种最先进的文本分类器方法，我们想要探究这些模型是否实际学习如何组成句子的含义，还是只使用一些关键词典。为了检验我们的假设，我们构造了数据集，其中列车和测试分割没有这些词典的直接重叠。我们研究各种文本分类器，并观察这些数据集有很大的性能下降。最后，我们表明即使是简单的正则化技术也可以提高这些数据集的性能。

##### URL
[http://arxiv.org/abs/1801.06261](http://arxiv.org/abs/1801.06261)

##### PDF
[http://arxiv.org/pdf/1801.06261](http://arxiv.org/pdf/1801.06261)

