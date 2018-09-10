---
layout: post
title: "Character-Aware Decoder for Neural Machine Translation"
date: 2018-09-06 21:26:31
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN NMT
author: Adithya Renduchintala, Pamela Shapiro, Kevin Duh, Philipp Koehn
mathjax: true
---

* content
{:toc}

##### Abstract
Standard neural machine translation (NMT) systems operate primarily on words, ignoring lower-level patterns of morphology. We present a character-aware decoder for NMT that can simultaneously work with both word-level and subword-level sequences which is designed to capture such patterns. We achieve character-awareness by augmenting both the softmax and embedding layers of an attention-based encoder-decoder network with convolutional neural networks that operate on spelling of a word (or subword). While character-aware embeddings have been successfully used in the source-side, we find that mixing character-aware embeddings with standard embeddings is crucial in the target-side. Furthermore, we show that a simple approximate softmax layer can be used for large target-side vocabularies which would otherwise require prohibitively large memory. We experiment on the TED multi-target dataset, translating English into 14 typologically diverse languages. We find that in this low-resource setting, the character-aware decoder provides consistent improvements over word-level and subword-level counterparts with BLEU score gains of up to +3.37.

##### Abstract (translated by Google)
标准神经机器翻译（NMT）系统主要在单词上运行，忽略了较低级别的形态学模式。我们提出了一种用于NMT的字符识别解码器，它可以同时处理用于捕获这种模式的字级和子级级序列。我们通过增加基于注意力的编码器 - 解码器网络的softmax和嵌入层来实现字符感知，其中卷积神经网络对单词（或子字）的拼写进行操作。虽然字符感知嵌入已成功用于源端，但我们发现将字符感知嵌入与标准嵌入混合在目标端是至关重要的。此外，我们表明，一个简单的近似softmax层可以用于大型目标端词汇表，否则需要过大的内存。我们在TED多目标数据集上进行实验，将英语翻译成14种不同的语言。我们发现，在这种低资源设置中，字符感知解码器提供了与字级和子字级相对应的一致改进，BLEU分数增益高达+3.37。

##### URL
[https://arxiv.org/abs/1809.02223](https://arxiv.org/abs/1809.02223)

##### PDF
[https://arxiv.org/pdf/1809.02223](https://arxiv.org/pdf/1809.02223)

