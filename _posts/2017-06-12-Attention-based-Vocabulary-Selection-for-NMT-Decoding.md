---
layout: post
title: "Attention-based Vocabulary Selection for NMT Decoding"
date: 2017-06-12 19:51:00
categories: arXiv_CL
tags: arXiv_CL NMT
author: Baskaran Sankaran, Markus Freitag, Yaser Al-Onaizan
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) models usually use large target vocabulary sizes to capture most of the words in the target language. The vocabulary size is a big factor when decoding new sentences as the final softmax layer normalizes over all possible target words. To address this problem, it is widely common to restrict the target vocabulary with candidate lists based on the source sentence. Usually, the candidate lists are a combination of external word-to-word aligner, phrase table entries or most frequent words. In this work, we propose a simple and yet novel approach to learn candidate lists directly from the attention layer during NMT training. The candidate lists are highly optimized for the current NMT model and do not need any external computation of the candidate pool. We show significant decoding speedup compared with using the entire vocabulary, without losing any translation quality for two language pairs.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型通常使用较大的目标词汇量来捕捉目标语言中的大部分词汇。当解码新句子时，词汇大小是一个很大的因素，因为最终的softmax层在所有可能的目标词上标准化。为了解决这个问题，基于源语句限制候选词表的目标词汇是非常普遍的。通常，候选列表是外部字对词对齐，短语表条目或最常用词的组合。在这项工作中，我们提出了一个简单而新颖的方法来在NMT培训期间直接从关注层学习候选人列表。候选列表针对当前的NMT模型进行了高度优化，并且不需要任何候选池的外部计算。与使用整个词汇表相比，我们显示了显着的解码加速，而不会损失任何两种语言对的翻译质量。

##### URL
[https://arxiv.org/abs/1706.03824](https://arxiv.org/abs/1706.03824)

##### PDF
[https://arxiv.org/pdf/1706.03824](https://arxiv.org/pdf/1706.03824)

