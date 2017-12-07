---
layout: post
title: "Handling Homographs in Neural Machine Translation"
date: 2017-08-22 06:48:27
categories: arXiv_CL
tags: arXiv_CL Face Embedding NMT
author: Frederick Liu, Han Lu, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
Homographs, words with different meanings but the same surface form, have long caused difficulty for machine translation systems, as it is difficult to select the correct translation based on the context. However, with the advent of neural machine translation (NMT) systems, which can theoretically take into account global sentential context, one may hypothesize that this problem has been alleviated. In this paper, we first provide empirical evidence that existing NMT systems in fact still have significant problems in properly translating ambiguous words. We then proceed to describe methods, inspired by the word sense disambiguation literature, that model the context of the input word with context-aware word embeddings that help to differentiate the word sense be- fore feeding it into the encoder. Experiments on three language pairs demonstrate that such models improve the performance of NMT systems both in terms of BLEU score and in the accuracy of translating homographs.

##### Abstract (translated by Google)
同形词，含义不同但表面形式相同的词，长期以来给机器翻译系统带来了困难，因为很难根据上下文选择正确的翻译。然而，随着神经机器翻译（NMT）系统的出现，理论上可以考虑到全球的语境，我们可以推测这个问题已经得到缓解。在本文中，我们首先提供的经验证据表明，现有的NMT系统事实上在正确翻译歧义词时仍然存在重大问题。然后，我们继续描述方法，从单词意义消歧文献的启发，用输入词的上下文建模上下文感知的词嵌入，有助于区分单词的意义之前，将其馈送到编码器。在三个语言对上的实验表明，这样的模型提高了NMT系统在BLEU评分和翻译同形异义词的准确性方面的性能。

##### URL
[https://arxiv.org/abs/1708.06510](https://arxiv.org/abs/1708.06510)

##### PDF
[https://arxiv.org/pdf/1708.06510](https://arxiv.org/pdf/1708.06510)

