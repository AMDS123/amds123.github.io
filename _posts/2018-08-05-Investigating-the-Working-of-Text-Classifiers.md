---
layout: post
title: "Investigating the Working of Text Classifiers"
date: 2018-08-05 16:08:59
categories: arXiv_CL
tags: arXiv_CL Regularization Text_Classification Classification
author: Devendra Singh Sachan, Manzil Zaheer, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Text classification is one of the most widely studied tasks in natural language processing. Motivated by the principle of compositionality, large multilayer neural network models have been employed for this task in an attempt to effectively utilize the constituent expressions. Almost all of the reported work train large networks using discriminative approaches, which come with a caveat of no proper capacity control, as they tend to latch on to any signal that may not generalize. Using various recent state-of-the-art approaches for text classification, we explore whether these models actually learn to compose the meaning of the sentences or still just focus on some keywords or lexicons for classifying the document. To test our hypothesis, we carefully construct datasets where the training and test splits have no direct overlap of such lexicons, but overall language structure would be similar. We study various text classifiers and observe that there is a big performance drop on these datasets. Finally, we show that even simple models with our proposed regularization techniques, which disincentivize focusing on key lexicons, can substantially improve classification accuracy.

##### Abstract (translated by Google)
文本分类是自然语言处理中研究最广泛的任务之一。在组合性原理的推动下，为了有效地利用组成表达式，已经采用大型多层神经网络模型来完成该任务。几乎所有报道的工作都使用有区别的方法对大型网络进行训练，这些方法伴随着一个没有适当容量控制的警告，因为它们倾向于锁定任何可能无法概括的信号。使用各种最新的最先进的文本分类方法，我们探索这些模型是否真正学会构成句子的意义，或者仍然只关注一些关键词或词典来分类文档。为了验证我们的假设，我们仔细构建了数据集，其中训练和测试分裂没有这些词典的直接重叠，但总体语言结构将是相似的。我们研究了各种文本分类器，并观察到这些数据集的性能下降很大。最后，我们表明，即使是简单的模型，我们提出的正则化技术，可以抑制对关键词典的关注，可以大大提高分类准确性。

##### URL
[http://arxiv.org/abs/1801.06261](http://arxiv.org/abs/1801.06261)

##### PDF
[http://arxiv.org/pdf/1801.06261](http://arxiv.org/pdf/1801.06261)

