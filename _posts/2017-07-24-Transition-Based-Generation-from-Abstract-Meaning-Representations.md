---
layout: post
title: "Transition-Based Generation from Abstract Meaning Representations"
date: 2017-07-24 14:52:32
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Timo Schick
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the task of generating English sentences from Abstract Meaning Representation (AMR) graphs. To cope with this task, we transform each input AMR graph into a structure similar to a dependency tree and annotate it with syntactic information by applying various predefined actions to it. Subsequently, a sentence is obtained from this tree structure by visiting its nodes in a specific order. We train maximum entropy models to estimate the probability of each individual action and devise an algorithm that efficiently approximates the best sequence of actions to be applied. Using a substandard language model, our generator achieves a Bleu score of 27.4 on the LDC2014T12 test set, the best result reported so far without using silver standard annotations from another corpus as additional training data.

##### Abstract (translated by Google)
这项工作解决了从抽象意义表示（AMR）图形生成英语句子的任务。为了处理这个任务，我们将每个输入的AMR图变换成一个类似于依赖树的结构，并通过对其应用各种预定义的动作来用句法信息对其进行注释。随后，通过以特定顺序访问其节点来从该树结构获得句子。我们训练最大熵模型来估计每个单独动作的概率，并设计一个算法，有效地逼近要应用的最佳动作序列。使用不合标准的语言模型，我们的生成器在LDC2014T12测试集上获得了27.4的Bleu得分，这是迄今为止报告的最好结果，而不使用来自另一个语料库的银标准注释作为额外的训练数据。

##### URL
[https://arxiv.org/abs/1707.07591](https://arxiv.org/abs/1707.07591)

##### PDF
[https://arxiv.org/pdf/1707.07591](https://arxiv.org/pdf/1707.07591)

