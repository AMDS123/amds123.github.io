---
layout: post
title: "SentencePiece: A simple and language independent subword tokenizer and detokenizer for Neural Text Processing"
date: 2018-08-19 16:49:06
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Taku Kudo, John Richardson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes SentencePiece, a language-independent subword tokenizer and detokenizer designed for Neural-based text processing, including Neural Machine Translation. It provides open-source C++ and Python implementations for subword units. While existing subword segmentation tools assume that the input is pre-tokenized into word sequences, SentencePiece can train subword models directly from raw sentences, which allows us to make a purely end-to-end and language independent system. We perform a validation experiment of NMT on English-Japanese machine translation, and find that it is possible to achieve comparable accuracy to direct subword training from raw sentences. We also compare the performance of subword training and segmentation with various configurations. SentencePiece is available under the Apache 2 license at https://github.com/google/sentencepiece.

##### Abstract (translated by Google)
本文描述了SentencePiece，一种独立于语言的子字标记器和解除器，设计用于基于神经的文本处理，包括神经机器翻译。它为子字单元提供开源C ++和Python实现。虽然现有的子词分词工具假设输入被预先标记为单词序列，但SentencePiece可以直接从原始句子训练子词模型，这使我们可以创建一个纯粹的端到端和语言无关的系统。我们对英日机器翻译进行了NMT验证实验，发现可以从原始句子中获得与直接子字训练相当的准确性。我们还将子字训练和分割的性能与各种配置进行比较。 SentencePiece可通过https://github.com/google/sentencepiece在Apache 2许可下获得。

##### URL
[http://arxiv.org/abs/1808.06226](http://arxiv.org/abs/1808.06226)

##### PDF
[http://arxiv.org/pdf/1808.06226](http://arxiv.org/pdf/1808.06226)

