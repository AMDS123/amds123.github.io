---
layout: post
title: "Generating Wikipedia by Summarizing Long Sequences"
date: 2018-01-30 20:07:01
categories: arXiv_CL
tags: arXiv_CL Salient Summarization
author: Peter J. Liu, Mohammad Saleh, Etienne Pot, Ben Goodrich, Ryan Sepassi, Lukasz Kaiser, Noam Shazeer
mathjax: true
---

* content
{:toc}

##### Abstract
We show that generating English Wikipedia articles can be approached as a multi- document summarization of source documents. We use extractive summarization to coarsely identify salient information and a neural abstractive model to generate the article. For the abstractive model, we introduce a decoder-only architecture that can scalably attend to very long sequences, much longer than typical encoder- decoder architectures used in sequence transduction. We show that this model can generate fluent, coherent multi-sentence paragraphs and even whole Wikipedia articles. When given reference documents, we show it can extract relevant factual information as reflected in perplexity, ROUGE scores and human evaluations.

##### Abstract (translated by Google)
我们表明，生成英文维基百科文章可以作为源文件的多文件汇总。我们使用抽取摘要来粗略地识别显着信息和神经抽象模型来生成文章。对于抽象模型，我们引入了一个只能解码的体系结构，它可以按照很长的序列进行扩展，比用于序列转换的典型编码器 - 解码器体系结构要长得多。我们表明，这个模型可以生成流畅，连贯的多句话段落，甚至整个维基百科的文章。当给出参考文献时，我们表明它可以提取相关的事实信息，如困惑，ROUGE分数和人类评价所反映的。

##### URL
[http://arxiv.org/abs/1801.10198](http://arxiv.org/abs/1801.10198)

##### PDF
[http://arxiv.org/pdf/1801.10198](http://arxiv.org/pdf/1801.10198)

