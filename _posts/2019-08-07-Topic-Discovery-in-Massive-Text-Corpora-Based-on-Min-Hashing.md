---
layout: post
title: "Topic Discovery in Massive Text Corpora Based on Min-Hashing"
date: 2019-08-07 06:41:03
categories: arXiv_CL
tags: arXiv_CL Quantitative
author: Gibran Fuentes-Pineda, Ivan Vladimir Meza-Ruiz
mathjax: true
---

* content
{:toc}

##### Abstract
The task of discovering topics in text corpora has been dominated by Latent Dirichlet Allocation and other Topic Models for over a decade. In order to apply these approaches to massive text corpora, the vocabulary needs to be reduced considerably and large computer clusters and/or GPUs are typically required. Moreover, the number of topics must be provided beforehand but this depends on the corpus characteristics and it is often difficult to estimate, especially for massive text corpora. Unfortunately, both topic quality and time complexity are sensitive to this choice. This paper describes an alternative approach to discover topics based on Min-Hashing, which can handle massive text corpora and large vocabularies using modest computer hardware and does not require to fix the number of topics in advance. The basic idea is to generate multiple random partitions of the corpus vocabulary to find sets of highly co-occurring words, which are then clustered to produce the final topics. In contrast to probabilistic topic models where topics are distributions over the complete vocabulary, the topics discovered by the proposed approach are sets of highly co-occurring words. Interestingly, these topics underlie various thematics with different levels of granularity. An extensive qualitative and quantitative evaluation using the 20 Newsgroups (18K), Reuters (800K), Spanish Wikipedia (1M), and English Wikipedia (5M) corpora shows that the proposed approach is able to consistently discover meaningful and coherent topics. Remarkably, the time complexity of the proposed approach is linear with respect to corpus and vocabulary size; a non-parallel implementation was able to discover topics from the entire English edition of Wikipedia with over 5 million documents and 1 million words in less than 7 hours.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.00938](http://arxiv.org/abs/1807.00938)

##### PDF
[http://arxiv.org/pdf/1807.00938](http://arxiv.org/pdf/1807.00938)

