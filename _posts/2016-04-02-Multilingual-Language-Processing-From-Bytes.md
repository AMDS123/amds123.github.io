---
layout: post
title: "Multilingual Language Processing From Bytes"
date: 2016-04-02 16:26:23
categories: arXiv_CL
tags: arXiv_CL RNN Recognition
author: Dan Gillick, Cliff Brunk, Oriol Vinyals, Amarnag Subramanya
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an LSTM-based model which we call Byte-to-Span (BTS) that reads text as bytes and outputs span annotations of the form [start, length, label] where start positions, lengths, and labels are separate entries in our vocabulary. Because we operate directly on unicode bytes rather than language-specific words or characters, we can analyze text in many languages with a single model. Due to the small vocabulary size, these multilingual models are very compact, but produce results similar to or better than the state-of- the-art in Part-of-Speech tagging and Named Entity Recognition that use only the provided training datasets (no external data sources). Our models are learning "from scratch" in that they do not rely on any elements of the standard pipeline in Natural Language Processing (including tokenization), and thus can run in standalone fashion on raw text.

##### Abstract (translated by Google)
我们描述了一个基于LSTM的模型，我们称之为字节到跨度（BTS），它读取文本作为字节，并输出形式[开始，长度，标签]的开始位置，长度和标签是单独条目的跨度注释词汇。因为我们直接使用unicode字节而不是特定于语言的单词或字符，所以我们可以使用单个模型分析多种语言的文本。由于词汇量小，这些多语言模型是非常紧凑的，但产生的结果类似于或优于现有技术的词性标注和命名实体识别，只使用提供的训练数据集（no外部数据源）。我们的模型是从头开始学习的，因为它们不依赖于自然语言处理（包括标记化）中标准流水线的任何元素，因此可以独立运行在原始文本上。

##### URL
[https://arxiv.org/abs/1512.00103](https://arxiv.org/abs/1512.00103)

##### PDF
[https://arxiv.org/pdf/1512.00103](https://arxiv.org/pdf/1512.00103)

