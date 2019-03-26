---
layout: post
title: "Cyclical Annealing Schedule: A Simple Approach to Mitigating KL Vanishing"
date: 2019-03-25 06:28:24
categories: arXiv_AI
tags: arXiv_AI Regularization Optimization Language_Model
author: Hao Fu*, Chunyuan Li*, Xiaodong Liu, Jianfeng Gao, Asli Celikyilmaz, Lawrence Carin
mathjax: true
---

* content
{:toc}

##### Abstract
Variational autoencoders (VAEs) with an auto-regressive decoder have been applied for many natural language processing (NLP) tasks. The VAE objective consists of two terms, (i) reconstruction and (ii) KL regularization, balanced by a weighting hyper-parameter \beta. One notorious training difficulty is that the KL term tends to vanish. In this paper we study scheduling schemes for \beta, and show that KL vanishing is caused by the lack of good latent codes in training the decoder at the beginning of optimization. 
 To remedy this, we propose a cyclical annealing schedule, which repeats the process of increasing \beta multiple times. This new procedure allows the progressive learning of more meaningful latent codes, by leveraging the informative representations of previous cycles as warm re-starts. The effectiveness of cyclical annealing is validated on a broad range of NLP tasks, including language modeling, dialog response generation and unsupervised language pre-training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10145](http://arxiv.org/abs/1903.10145)

##### PDF
[http://arxiv.org/pdf/1903.10145](http://arxiv.org/pdf/1903.10145)

