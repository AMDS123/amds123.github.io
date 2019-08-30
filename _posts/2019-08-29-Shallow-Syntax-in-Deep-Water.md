---
layout: post
title: "Shallow Syntax in Deep Water"
date: 2019-08-29 04:45:38
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Swabha Swayamdipta, Matthew Peters, Brendan Roof, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Shallow syntax provides an approximation of phrase-syntactic structure of sentences; it can be produced with high accuracy, and is computationally cheap to obtain. We investigate the role of shallow syntax-aware representations for NLP tasks using two techniques. First, we enhance the ELMo architecture to allow pretraining on predicted shallow syntactic parses, instead of just raw text, so that contextual embeddings make use of shallow syntactic context. Our second method involves shallow syntactic features obtained automatically on downstream task data. Neither approach leads to a significant gain on any of the four downstream tasks we considered relative to ELMo-only baselines. Further analysis using black-box probes confirms that our shallow-syntax-aware contextual embeddings do not transfer to linguistic tasks any more easily than ELMo's embeddings. We take these findings as evidence that ELMo-style pretraining discovers representations which make additional awareness of shallow syntax redundant.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11047](http://arxiv.org/abs/1908.11047)

##### PDF
[http://arxiv.org/pdf/1908.11047](http://arxiv.org/pdf/1908.11047)

