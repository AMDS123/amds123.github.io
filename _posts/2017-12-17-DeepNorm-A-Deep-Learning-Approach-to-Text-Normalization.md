---
layout: post
title: "DeepNorm-A Deep Learning Approach to Text Normalization"
date: 2017-12-17 18:31:26
categories: arXiv_CL
tags: arXiv_CL RNN Classification Deep_Learning Prediction
author: Maryam Zare, Shaurya Rohatgi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an simple yet sophisticated approach to the challenge by Sproat and Jaitly (2016)- given a large corpus of written text aligned to its normalized spoken form, train an RNN to learn the correct normalization function. Text normalization for a token seems very straightforward without it's context. But given the context of the used token and then normalizing becomes tricky for some classes. We present a novel approach in which the prediction of our classification algorithm is used by our sequence to sequence model to predict the normalized text of the input token. Our approach takes very less time to learn and perform well unlike what has been reported by Google (5 days on their GPU cluster). We have achieved an accuracy of 97.62 which is impressive given the resources we use. Our approach is using the best of both worlds, gradient boosting - state of the art in most classification tasks and sequence to sequence learning - state of the art in machine translation. We present our experiments and report results with various parameter settings.

##### Abstract (translated by Google)
本文提出了Sproat和Jaitly（2016）针对这一挑战的一个简单而复杂的方法 - 由于大量的书面文本与规范化的口语形式相一致，因此需要训练一个RNN来学习正确的规范化函数。标记的文本标准化看起来非常简单，没有上下文。但是，考虑到使用的标记的上下文，然后正常化一些类变得棘手。我们提出了一种新颖的方法，其中我们的分类算法的预测被我们的序列用于序列模型来预测输入标记的标准化文本。我们的方法花费的时间非常少，不像Google报道的那样（在他们的GPU集群上5天）学习和执行得不错。我们已经达到了97.62的准确度，考虑到我们使用的资源，令人印象深刻。我们的方法是利用两全其美，梯度提升 - 大多数分类任务的先进技术水平，以及序列学习顺序 - 机器翻译领域的先进水平。我们提供我们的实验和报告结果与各种参数设置。

##### URL
[http://arxiv.org/abs/1712.06994](http://arxiv.org/abs/1712.06994)

##### PDF
[http://arxiv.org/pdf/1712.06994](http://arxiv.org/pdf/1712.06994)

