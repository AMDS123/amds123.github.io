---
layout: post
title: "Variational Pretraining for Semi-supervised Text Classification"
date: 2019-06-05 18:40:37
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification
author: Suchin Gururangan, Tam Dang, Dallas Card, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce VAMPIRE, a lightweight pretraining framework for effective text classification when data and computing resources are limited. We pretrain a unigram document model as a variational autoencoder on in-domain, unlabeled data and use its internal states as features in a downstream classifier. Empirically, we show the relative strength of VAMPIRE against computationally expensive contextual embeddings and other popular semi-supervised baselines under low resource settings. We also find that fine-tuning to in-domain data is crucial to achieving decent performance from contextual embeddings when working with limited supervision. We accompany this paper with code to pretrain and use VAMPIRE embeddings in downstream tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02242](http://arxiv.org/abs/1906.02242)

##### PDF
[http://arxiv.org/pdf/1906.02242](http://arxiv.org/pdf/1906.02242)

