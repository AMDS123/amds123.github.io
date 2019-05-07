---
layout: post
title: "An Evaluation of Transfer Learning for Classifying Sales Engagement Emails at Large Scale"
date: 2019-04-19 18:11:54
categories: arXiv_CL
tags: arXiv_CL Embedding Transfer_Learning Language_Model
author: Yong Liu, Pavel Dmitriev, Yifei Huang, Andrew Brooks, Li Dong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper conducts an empirical investigation to evaluate transfer learning for classifying sales engagement emails arising from digital sales engagement platforms. Given the complexity of content and context of sales engagement, lack of standardized large corpora and benchmarks, limited labeled examples and heterogenous context of intent, this real-world use case poses both a challenge and an opportunity for adopting a transfer learning approach. We propose an evaluation framework to assess a high performance transfer learning (HPTL) approach in three key areas in addition to commonly used accuracy metrics: 1) effective embeddings and pretrained language model usage, 2) minimum labeled samples requirement and 3) transfer learning implementation strategies. We use in-house sales engagement email samples as the experiment dataset, which includes over 3000 emails labeled as positive, objection, unsubscribe, or not-sure. We discuss our findings on evaluating BERT, ELMo, Flair and GloVe embeddings with both feature-based and fine-tuning approaches and their scalability on a GPU cluster with increasingly larger labeled samples. Our results show that fine-tuning of the BERT model outperforms with as few as 300 labeled samples, but underperforms with fewer than 300 labeled samples, relative to all the feature-based approaches using different embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01971](http://arxiv.org/abs/1905.01971)

##### PDF
[http://arxiv.org/pdf/1905.01971](http://arxiv.org/pdf/1905.01971)

