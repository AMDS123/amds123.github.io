---
layout: post
title: "Splitting source code identifiers using Bidirectional LSTM Recurrent Neural Network"
date: 2018-05-26 06:46:55
categories: arXiv_CL
tags: arXiv_CL RNN
author: Vadim Markovtsev, Waren Long, Egor Bulychev, Romain Keramitas, Konstantin Slavnov, Gabor Markowski
mathjax: true
---

* content
{:toc}

##### Abstract
Programmers make rich use of natural language in the source code they write through identifiers and comments. Source code identifiers are selected from a pool of tokens which are strongly related to the meaning, naming conventions, and context. These tokens are often combined to produce more precise and obvious designations. Such multi-part identifiers count for 97% of all naming tokens in the Public Git Archive - the largest dataset of Git repositories to date. We introduce a bidirectional LSTM recurrent neural network to detect subtokens in source code identifiers. We trained that network on 41.7 million distinct splittable identifiers collected from 182,014 open source projects in Public Git Archive, and show that it outperforms several other machine learning models. The proposed network can be used to improve the upstream models which are based on source code identifiers, as well as improving developer experience allowing writing code without switching the keyboard case.

##### Abstract (translated by Google)
程序员在通过标识符和注释写入的源代码中丰富地使用自然语言。源代码标识符是从与含义，命名约定和上下文紧密相关的令牌池中选择的。这些令牌通常结合起来产生更精确和明显的名称。这种多部分标识符占公共Git存档中所有命名标记的97％ -  Git存储库迄今为止最大的数据集。我们引入了一个双向LSTM递归神经网络来检测源代码标识符中的子代。我们在Public Git Archive的182,014个开源项目中收集了4170万个不同的可拆分标识符，并且表明它比其他几种机器学习模型更好。建议的网络可用于改进基于源代码标识符的上游模型，以及改进开发人员的体验，允许在不切换键盘外壳的情况下编写代码。

##### URL
[http://arxiv.org/abs/1805.11651](http://arxiv.org/abs/1805.11651)

##### PDF
[http://arxiv.org/pdf/1805.11651](http://arxiv.org/pdf/1805.11651)

