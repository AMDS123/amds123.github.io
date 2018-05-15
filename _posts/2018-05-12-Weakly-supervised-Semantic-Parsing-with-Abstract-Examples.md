---
layout: post
title: "Weakly-supervised Semantic Parsing with Abstract Examples"
date: 2018-05-12 20:12:13
categories: arXiv_AI
tags: arXiv_AI
author: Omer Goldman, Veronica Latcinnik, Udi Naveh, Amir Globerson, Jonathan Berant
mathjax: true
---

* content
{:toc}

##### Abstract
Training semantic parsers from weak supervision (denotations) rather than strong supervision (programs) complicates training in two ways. First, a large search space of potential programs needs to be explored at training time to find a correct program. Second, spurious programs that accidentally lead to a correct denotation add noise to training. In this work we propose that in closed worlds with clear semantic types, one can substantially alleviate these problems by utilizing an abstract representation, where tokens in both the language utterance and program are lifted to an abstract form. We show that these abstractions can be defined with a handful of lexical rules and that they result in sharing between different examples that alleviates the difficulties in training. To test our approach, we develop the first semantic parser for CNLVR, a challenging visual reasoning dataset, where the search space is large and overcoming spuriousness is critical, because denotations are either TRUE or FALSE, and thus random programs are likely to lead to a correct denotation. Our method substantially improves performance, and reaches 82.5% accuracy, a 14.7% absolute accuracy improvement compared to the best reported accuracy so far.

##### Abstract (translated by Google)
从弱监督（指示）而不是强有力的监督（程序）训练语义解析器会使训练以两种方式复杂化。首先，需要在培训时探索潜在课程的大型搜索空间，以找到正确的课程。其次，意外导致正确外延的虚假程序会给训练带来噪音。在这项工作中，我们提出，在封闭的世界中，语义类型清晰，可以通过利用抽象表示来大幅缓解这些问题，其中语言话语和程序中的令牌都被提升为抽象形式。我们证明这些抽象可以用一些词汇规则来定义，并且它们导致不同例子之间的共享，从而减轻训练中的困难。为了测试我们的方法，我们为CNLVR开发了第一个语义解析器，这是一个具有挑战性的视觉推理数据集，其中搜索空间很大并且克服虚假性至关重要，因为符号是TRUE或FALSE，因此随机程序可能会导致正确的表示。我们的方法大大提高了性能，并且达到了82.5％的准确度，与迄今为止报告的最高准确度相比，绝对准确度提高了14.7％。

##### URL
[http://arxiv.org/abs/1711.05240](http://arxiv.org/abs/1711.05240)

##### PDF
[http://arxiv.org/pdf/1711.05240](http://arxiv.org/pdf/1711.05240)

