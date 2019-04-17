---
layout: post
title: "Positional Encoding to Control Output Sequence Length"
date: 2019-04-16 02:48:11
categories: arXiv_CL
tags: arXiv_CL Summarization Embedding
author: Sho Takase, Naoaki Okazaki
mathjax: true
---

* content
{:toc}

##### Abstract
Neural encoder-decoder models have been successful in natural language generation tasks. However, real applications of abstractive summarization must consider additional constraint that a generated summary should not exceed a desired length. In this paper, we propose a simple but effective extension of a sinusoidal positional encoding (Vaswani et al., 2017) to enable neural encoder-decoder model to preserves the length constraint. Unlike in previous studies where that learn embeddings representing each length, the proposed method can generate a text of any length even if the target length is not present in training data. The experimental results show that the proposed method can not only control the generation length but also improve the ROUGE scores.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07418](http://arxiv.org/abs/1904.07418)

##### PDF
[http://arxiv.org/pdf/1904.07418](http://arxiv.org/pdf/1904.07418)

