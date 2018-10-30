---
layout: post
title: "Low-shot Learning via Covariance-Preserving Adversarial Augmentation Networks"
date: 2018-10-27 23:09:10
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Hang Gao, Zheng Shou, Alireza Zareian, Hanwang Zhang, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks suffer from over-fitting and catastrophic forgetting when trained with small data. One natural remedy for this problem is data augmentation, which has been recently shown to be effective. However, previous works either assume that intra-class variances can always be generalized to new classes, or employ naive generation methods to hallucinate finite examples without modeling their latent distributions. In this work, we propose Covariance-Preserving Adversarial Augmentation Networks to overcome existing limits of low-shot learning. Specifically, a novel Generative Adversarial Network is designed to model the latent distribution of each novel class given its related base counterparts. Since direct estimation on novel classes can be inductively biased, we explicitly preserve covariance information as the "variability" of base examples during the generation process. Empirical results show that our model can generate realistic yet diverse examples, leading to substantial improvements on the ImageNet benchmark over the state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11730](http://arxiv.org/abs/1810.11730)

##### PDF
[http://arxiv.org/pdf/1810.11730](http://arxiv.org/pdf/1810.11730)

