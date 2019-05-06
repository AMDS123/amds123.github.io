---
layout: post
title: "Integrating Lexical and Temporal Signals in Neural Ranking Models for Searching Social Media Streams"
date: 2017-07-25 02:29:31
categories: arXiv_CV
tags: arXiv_CV Knowledge RNN
author: Jinfeng Rao, Hua He, Haotian Zhang, Ferhan Ture, Royal Sequiera, Salman Mohammed, Jimmy Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Time is an important relevance signal when searching streams of social media posts. The distribution of document timestamps from the results of an initial query can be leveraged to infer the distribution of relevant documents, which can then be used to rerank the initial results. Previous experiments have shown that kernel density estimation is a simple yet effective implementation of this idea. This paper explores an alternative approach to mining temporal signals with recurrent neural networks. Our intuition is that neural networks provide a more expressive framework to capture the temporal coherence of neighboring documents in time. To our knowledge, we are the first to integrate lexical and temporal signals in an end-to-end neural network architecture, in which existing neural ranking models are used to generate query-document similarity vectors that feed into a bidirectional LSTM layer for temporal modeling. Our results are mixed: existing neural models for document ranking alone yield limited improvements over simple baselines, but the integration of lexical and temporal signals yield significant improvements over competitive temporal baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.07792](https://arxiv.org/abs/1707.07792)

##### PDF
[https://arxiv.org/pdf/1707.07792](https://arxiv.org/pdf/1707.07792)

