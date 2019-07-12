---
layout: post
title: "Topic Modeling in Embedding Spaces"
date: 2019-07-08 03:50:57
categories: arXiv_CL
tags: arXiv_CL Embedding Inference
author: Adji B. Dieng, Francisco J. R. Ruiz, David M. Blei
mathjax: true
---

* content
{:toc}

##### Abstract
Topic modeling analyzes documents to learn meaningful patterns of words. However, existing topic models fail to learn interpretable topics when working with large and heavy-tailed vocabularies. To this end, we develop the Embedded Topic Model (ETM), a generative model of documents that marries traditional topic models with word embeddings. In particular, it models each word with a categorical distribution whose natural parameter is the inner product between a word embedding and an embedding of its assigned topic. To fit the ETM, we develop an efficient amortized variational inference algorithm. The ETM discovers interpretable topics even with large vocabularies that include rare words and stop words. It outperforms existing document models, such as latent Dirichlet allocation (LDA), in terms of both topic quality and predictive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04907](http://arxiv.org/abs/1907.04907)

##### PDF
[http://arxiv.org/pdf/1907.04907](http://arxiv.org/pdf/1907.04907)

