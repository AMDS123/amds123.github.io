---
layout: post
title: "Optimizing Segmentation Granularity for Neural Machine Translation"
date: 2018-10-19 18:47:02
categories: arXiv_CL
tags: arXiv_CL Segmentation Embedding NMT
author: Elizabeth Salesky, Andrew Runge, Alex Coda, Jan Niehues, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
In neural machine translation (NMT), it is has become standard to translate using subword units to allow for an open vocabulary and improve accuracy on infrequent words. Byte-pair encoding (BPE) and its variants are the predominant approach to generating these subwords, as they are unsupervised, resource-free, and empirically effective. However, the granularity of these subword units is a hyperparameter to be tuned for each language and task, using methods such as grid search. Tuning may be done inexhaustively or skipped entirely due to resource constraints, leading to sub-optimal performance. In this paper, we propose a method to automatically tune this parameter using only one training pass. We incrementally introduce new vocabulary online based on the held-out validation loss, beginning with smaller, general subwords and adding larger, more specific units over the course of training. Our method matches the results found with grid search, optimizing segmentation granularity without any additional training time. We also show benefits in training efficiency and performance improvements for rare words due to the way embeddings for larger units are incrementally constructed by combining those from smaller units.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08641](http://arxiv.org/abs/1810.08641)

##### PDF
[http://arxiv.org/pdf/1810.08641](http://arxiv.org/pdf/1810.08641)

