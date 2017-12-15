---
layout: post
title: "Improved Transition-Based Parsing by Modeling Characters instead of Words with LSTMs"
date: 2015-08-11 17:33:47
categories: arXiv_CL
tags: arXiv_CL Face RNN
author: Miguel Ballesteros, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We present extensions to a continuous-state dependency parsing method that makes it applicable to morphologically rich languages. Starting with a high-performance transition-based parser that uses long short-term memory (LSTM) recurrent neural networks to learn representations of the parser state, we replace lookup-based word representations with representations constructed from the orthographic representations of the words, also using LSTMs. This allows statistical sharing across word forms that are similar on the surface. Experiments for morphologically rich languages show that the parsing model benefits from incorporating the character-based encodings of words.

##### Abstract (translated by Google)
我们提出了一个连续状态依赖分析方法的扩展，使其适用于形态丰富的语言。从使用长时间短期记忆（LSTM）递归神经网络的高性能基于转换的解析器开始学习解析器状态的表示，我们用基于字的正交表示构造的表示替换基于查找的词表示，使用LSTMs。这允许在表面上类似的词形式上进行统计共享。形态丰富的语言的实验表明，分析模型受益于结合基于字符的单词编码。

##### URL
[https://arxiv.org/abs/1508.00657](https://arxiv.org/abs/1508.00657)

##### PDF
[https://arxiv.org/pdf/1508.00657](https://arxiv.org/pdf/1508.00657)

