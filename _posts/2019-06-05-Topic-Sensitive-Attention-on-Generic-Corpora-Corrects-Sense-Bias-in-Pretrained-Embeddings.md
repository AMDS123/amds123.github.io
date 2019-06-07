---
layout: post
title: "Topic Sensitive Attention on Generic Corpora Corrects Sense Bias in Pretrained Embeddings"
date: 2019-06-05 07:15:06
categories: arXiv_CL
tags: arXiv_CL Regularization Attention Embedding
author: Vihari Piratla, Sunita Sarawagi, Soumen Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Given a small corpus $\mathcal D_T$ pertaining to a limited set of focused topics, our goal is to train embeddings that accurately capture the sense of words in the topic in spite of the limited size of $\mathcal D_T$. These embeddings may be used in various tasks involving $\mathcal D_T$. A popular strategy in limited data settings is to adapt pre-trained embeddings $\mathcal E$ trained on a large corpus. To correct for sense drift, fine-tuning, regularization, projection, and pivoting have been proposed recently. Among these, regularization informed by a word's corpus frequency performed well, but we improve upon it using a new regularizer based on the stability of its cooccurrence with other words. However, a thorough comparison across ten topics, spanning three tasks, with standardized settings of hyper-parameters, reveals that even the best embedding adaptation strategies provide small gains beyond well-tuned baselines, which many earlier comparisons ignored. In a bold departure from adapting pretrained embeddings, we propose using $\mathcal D_T$ to probe, attend to, and borrow fragments from any large, topic-rich source corpus (such as Wikipedia), which need not be the corpus used to pretrain embeddings. This step is made scalable and practical by suitable indexing. We reach the surprising conclusion that even limited corpus augmentation is more useful than adapting embeddings, which suggests that non-dominant sense information may be irrevocably obliterated from pretrained embeddings and cannot be salvaged by adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02688](http://arxiv.org/abs/1906.02688)

##### PDF
[http://arxiv.org/pdf/1906.02688](http://arxiv.org/pdf/1906.02688)

