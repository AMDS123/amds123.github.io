---
layout: post
title: "Generative Adversarial Speaker Embedding Networks for Domain Robust End-to-End Speaker Verification"
date: 2018-11-07 18:23:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding
author: Gautam Bhattacharya, Joao Monteiro, Jahangir Alam, Patrick Kenny
mathjax: true
---

* content
{:toc}

##### Abstract
This article presents a novel approach for learning domain-invariant speaker embeddings using Generative Adversarial Networks. The main idea is to confuse a domain discriminator so that is can't tell if embeddings are from the source or target domains. We train several GAN variants using our proposed framework and apply them to the speaker verification task. On the challenging NIST-SRE 2016 dataset, we are able to match the performance of a strong baseline x-vector system. In contrast to the the baseline systems which are dependent on dimensionality reduction (LDA) and an external classifier (PLDA), our proposed speaker embeddings can be scored using simple cosine distance. This is achieved by optimizing our models end-to-end, using an angular margin loss function. Furthermore, we are able to significantly boost verification performance by averaging our different GAN models at the score level, achieving a relative improvement of 7.2% over the baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03063](http://arxiv.org/abs/1811.03063)

##### PDF
[http://arxiv.org/pdf/1811.03063](http://arxiv.org/pdf/1811.03063)

