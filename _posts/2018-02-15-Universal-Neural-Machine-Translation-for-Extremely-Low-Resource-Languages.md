---
layout: post
title: "Universal Neural Machine Translation for Extremely Low Resource Languages"
date: 2018-02-15 00:35:08
categories: arXiv_CL
tags: arXiv_CL
author: Jiatao Gu, Hany Hassan, Jacob Devlin, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new universal machine translation approach focusing on languages with a limited amount of parallel data. Our proposed approach utilizes a transfer-learning approach to share lexical and sentences level representations across multiple source languages into one target language. The lexical part is shared through a Universal Lexical Representation to support multi-lingual word-level sharing. The sentence-level sharing is represented by a model of experts from all source languages that share the source encoders with all other languages. This enables the low-resource language to utilize the lexical and sentence representations of the higher resource languages. Our approach is able to achieve 23 BLEU on Romanian-English WMT2016 using a tiny parallel corpus of 6k sentences, compared to the 18 BLEU of strong baseline system which uses multi-lingual training and back-translation.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的通用机器翻译方法，专注于具有有限数量并行数据的语言。我们提出的方法利用传递学习方法将跨多种源语言的词汇和句子级别表示分享为一种目标语言。词汇部分通过通用词汇表示来共享，以支持多语言字级共享。句级共享由来自所有源语言的专家模型表示，这些语言与所有其他语言共享源编码器。这使得低资源语言能够利用较高资源语言的词汇和句子表示。我们的方法能够使用6k句子的微小平行语料库在罗马尼亚语 - 英语WMT2016上实现23 BLEU，而使用多语言训练和回译的强基线系统的18 BLEU与BLEU相比较。

##### URL
[https://arxiv.org/abs/1802.05368](https://arxiv.org/abs/1802.05368)

##### PDF
[https://arxiv.org/pdf/1802.05368](https://arxiv.org/pdf/1802.05368)

