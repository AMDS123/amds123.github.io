---
layout: post
title: "Improving Abstraction in Text Summarization"
date: 2018-08-23 19:19:27
categories: arXiv_CL
tags: arXiv_CL Knowledge Summarization Language_Model
author: Wojciech Kry&#x15b;ci&#x144;ski, Romain Paulus, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive text summarization aims to shorten long text documents into a human readable form that contains the most important facts from the original document. However, the level of actual abstraction as measured by novel phrases that do not appear in the source document remains low in existing approaches. We propose two techniques to improve the level of abstraction of generated summaries. First, we decompose the decoder into a contextual network that retrieves relevant parts of the source document, and a pretrained language model that incorporates prior knowledge about language generation. Second, we propose a novelty metric that is optimized directly through policy learning to encourage the generation of novel phrases. Our model achieves results comparable to state-of-the-art models, as determined by ROUGE scores and human evaluations, while achieving a significantly higher level of abstraction as measured by n-gram overlap with the source document.

##### Abstract (translated by Google)
抽象文本摘要旨在将长文本文档缩短为包含原始文档中最重要事实的人类可读形式。然而，在现有方法中，通过未出现在源文档中的新颖短语测量的实际抽象水平仍然很低。我们提出了两种技术来提高生成的摘要的抽象级别。首先，我们将解码器分解为检索源文档的相关部分的上下文网络，以及包含有关语言生成的先验知识的预训练语言模型。其次，我们提出了一种新颖度量，它通过政策学习直接优化，以鼓励创造新颖的短语。我们的模型获得了与最新模型相当的结果，由ROUGE分数和人工评估确定，同时通过与源文档的n-gram重叠来实现显着更高的抽象水平。

##### URL
[http://arxiv.org/abs/1808.07913](http://arxiv.org/abs/1808.07913)

##### PDF
[http://arxiv.org/pdf/1808.07913](http://arxiv.org/pdf/1808.07913)

