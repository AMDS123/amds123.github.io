---
layout: post
title: "Modeling Coherence for Neural Machine Translation with Dynamic and Topic Caches"
date: 2018-06-14 09:25:29
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Shaohui Kuang, Deyi Xiong, Weihua Luo, Guodong Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Sentences in a well-formed text are connected to each other via various links to form the cohesive structure of the text. Current neural machine translation (NMT) systems translate a text in a conventional sentence-by-sentence fashion, ignoring such cross-sentence links and dependencies. This may lead to generate an incoherent target text for a coherent source text. In order to handle this issue, we propose a cache-based approach to modeling coherence for neural machine translation by capturing contextual information either from recently translated sentences or the entire document. Particularly, we explore two types of caches: a dynamic cache, which stores words from the best translation hypotheses of preceding sentences, and a topic cache, which maintains a set of target-side topical words that are semantically related to the document to be translated. On this basis, we build a new layer to score target words in these two caches with a cache-based neural model. Here the estimated probabilities from the cache-based neural model are combined with NMT probabilities into the final word prediction probabilities via a gating mechanism. Finally, the proposed cache-based neural model is trained jointly with NMT system in an end-to-end manner. Experiments and analysis presented in this paper demonstrate that the proposed cache-based model achieves substantial improvements over several state-of-the-art SMT and NMT baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.11221](https://arxiv.org/abs/1711.11221)

##### PDF
[https://arxiv.org/pdf/1711.11221](https://arxiv.org/pdf/1711.11221)

