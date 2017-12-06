---
layout: post
title: 'Look-ahead Attention for Generation in Neural Machine Translation'
date: 2017-08-30 11:27:02
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Long Zhou, Jiajun Zhang, Chengqing Zong
---

* content
{:toc}

##### Abstract
The attention model has become a standard component in neural machine translation (NMT) and it guides translation process by selectively focusing on parts of the source sentence when predicting each target word. However, we find that the generation of a target word does not only depend on the source sentence, but also rely heavily on the previous generated target words, especially the distant words which are difficult to model by using recurrent neural networks. To solve this problem, we propose in this paper a novel look-ahead attention mechanism for generation in NMT, which aims at directly capturing the dependency relationship between target words. We further design three patterns to integrate our look-ahead attention into the conventional attention model. Experiments on NIST Chinese-to-English and WMT English-to-German translation tasks show that our proposed look-ahead attention mechanism achieves substantial improvements over state-of-the-art baselines.

##### Abstract (translated by Google)
注意模型已经成为神经机器翻译（NMT）的一个标准组成部分，它在预测每个目标单词时，通过选择性地关注源句子的部分来指导翻译过程。然而，我们发现目标词的生成不仅依赖于源语句，而且还严重依赖于以前生成的目标词，尤其是使用递归神经网络难以建模的远处词。为了解决这个问题，本文提出了一种新颖的NMT生成关注机制，旨在直接捕获目标词之间的依赖关系。我们进一步设计了三种模式，将我们的前瞻性注意力集成到传统的注意模式中。 NIST中英文和WMT英文到德文翻译任务的实验表明，我们提出的预见性关注机制比最先进的基线实现了实质性的改进。

##### URL
[https://arxiv.org/abs/1708.09217](https://arxiv.org/abs/1708.09217)

