---
layout: post
title: "Fast Lexically Constrained Decoding with Dynamic Beam Allocation for Neural Machine Translation"
date: 2018-04-18 09:06:11
categories: arXiv_CL
tags: arXiv_CL NMT Relation
author: Matt Post, David Vilar
mathjax: true
---

* content
{:toc}

##### Abstract
The end-to-end nature of neural machine translation (NMT) removes many ways of manually guiding the translation process that were available in older paradigms. Recent work, however, has introduced a new capability: lexically constrained or guided decoding, a modification to beam search that forces the inclusion of pre-specified words and phrases in the output. However, while theoretically sound, existing approaches have computational complexities that are either linear (Hokamp and Liu, 2017) or exponential (Anderson et al., 2017) in the number of constraints. We present a algorithm for lexically constrained decoding with a complexity of O(1) in the number of constraints. We demonstrate the algorithms remarkable ability to properly place these constraints, and use it to explore the shaky relationship between model and BLEU scores. Our implementation is available as part of Sockeye.

##### Abstract (translated by Google)
神经机器翻译（NMT）的端到端特性消除了许多手动指导​​旧版范例中可用的翻译过程的方式。然而，最近的工作引入了一种新的功能：词汇约束或导向解码，对波束搜索的修改，强制在输出中包含预先指定的单词和短语。然而，虽然理论上合理，但现有方法的计算复杂性要么是线性的（Hokamp和Liu，2017），要么是指数性的（Anderson等，2017）。我们提出了一个在约束数量上具有O（1）复杂度的词汇约束解码算法。我们演示了算法卓越的能力来正确放置这些约束，并用它来探索模型与BLEU分数之间不稳定的关系。我们的实施可作为Sockeye的一部分。

##### URL
[https://arxiv.org/abs/1804.06609](https://arxiv.org/abs/1804.06609)

##### PDF
[https://arxiv.org/pdf/1804.06609](https://arxiv.org/pdf/1804.06609)

