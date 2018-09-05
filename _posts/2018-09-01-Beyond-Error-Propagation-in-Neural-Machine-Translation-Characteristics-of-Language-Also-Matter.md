---
layout: post
title: "Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter"
date: 2018-09-01 06:06:20
categories: arXiv_CL
tags: arXiv_CL Summarization RNN Relation
author: Lijun Wu, Xu Tan, Di He, Fei Tian, Tao Qin, Jianhuang Lai, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation usually adopts autoregressive models and suffers from exposure bias as well as the consequent error propagation problem. Many previous works have discussed the relationship between error propagation and the \emph{accuracy drop} (i.e., the left part of the translated sentence is often better than its right part in left-to-right decoding models) problem. In this paper, we conduct a series of analyses to deeply understand this problem and get several interesting findings. (1) The role of error propagation on accuracy drop is overstated in the literature, although it indeed contributes to the accuracy drop problem. (2) Characteristics of a language play a more important role in causing the accuracy drop: the left part of the translation result in a right-branching language (e.g., English) is more likely to be more accurate than its right part, while the right part is more accurate for a left-branching language (e.g., Japanese). Our discoveries are confirmed on different model structures including Transformer and RNN, and in other sequence generation tasks such as text summarization.

##### Abstract (translated by Google)
神经机器翻译通常采用自回归模型，并且受到曝光偏差以及随之而来的误差传播问题的影响。许多以前的工作已经讨论了错误传播与\ emph {精度下降}之间的关系（即，翻译句子的左侧部分通常比左侧到右侧解码模型中的右侧部分更好）问题。在本文中，我们进行了一系列分析，以深入理解这个问题，并获得一些有趣的发现。 （1）误差传播对精度下降的作用在文献中被夸大了，尽管它确实有助于精度下降问题。 （2）语言的特征在导致准确性下降方面起着更重要的作用：翻译结果的左侧部分采用右分支语言（例如英语）更可能比右侧部分更准确，而右侧部分对于左分支语言（例如，日语）更准确。我们的发现在不同的模型结构上得到了证实，包括Transformer和RNN，以及其他序列生成任务，如文本摘要。

##### URL
[http://arxiv.org/abs/1809.00120](http://arxiv.org/abs/1809.00120)

##### PDF
[http://arxiv.org/pdf/1809.00120](http://arxiv.org/pdf/1809.00120)

