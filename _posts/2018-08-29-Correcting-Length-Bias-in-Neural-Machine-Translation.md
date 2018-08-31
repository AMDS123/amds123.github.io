---
layout: post
title: "Correcting Length Bias in Neural Machine Translation"
date: 2018-08-29 18:33:11
categories: arXiv_CL
tags: arXiv_CL NMT
author: Kenton Murray, David Chiang
mathjax: true
---

* content
{:toc}

##### Abstract
We study two problems in neural machine translation (NMT). First, in beam search, whereas a wider beam should in principle help translation, it often hurts NMT. Second, NMT has a tendency to produce translations that are too short. Here, we argue that these problems are closely related and both rooted in label bias. We show that correcting the brevity problem almost eliminates the beam problem; we compare some commonly-used methods for doing this, finding that a simple per-word reward works well; and we introduce a simple and quick way to tune this reward using the perceptron algorithm.

##### Abstract (translated by Google)
我们研究了神经机器翻译（NMT）中的两个问题。首先，在波束搜索中，虽然更宽的波束原则上应该帮助翻译，但它经常会伤害NMT。其次，NMT倾向于产生太短的翻译。在这里，我们认为这些问题密切相关，并且都源于标签偏见。我们证明纠正简洁问题几乎消除了梁问题;我们比较了一些常用的方法，发现一个简单的单词奖励效果很好;我们介绍了一种使用感知器算法调整此奖励的简单快捷的方法。

##### URL
[http://arxiv.org/abs/1808.10006](http://arxiv.org/abs/1808.10006)

##### PDF
[http://arxiv.org/pdf/1808.10006](http://arxiv.org/pdf/1808.10006)

