---
layout: post
title: "Document Hashing with Mixture-Prior Generative Models"
date: 2019-08-29 07:29:28
categories: arXiv_CL
tags: arXiv_CL
author: Wei Dong, Qinliang Su, Dinghan Shen, Changyou Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing is promising for large-scale information retrieval tasks thanks to the efficiency of distance evaluation between binary codes. Generative hashing is often used to generate hashing codes in an unsupervised way. However, existing generative hashing methods only considered the use of simple priors, like Gaussian and Bernoulli priors, which limits these methods to further improve their performance. In this paper, two mixture-prior generative models are proposed, under the objective to produce high-quality hashing codes for documents. Specifically, a Gaussian mixture prior is first imposed onto the variational auto-encoder (VAE), followed by a separate step to cast the continuous latent representation of VAE into binary code. To avoid the performance loss caused by the separate casting, a model using a Bernoulli mixture prior is further developed, in which an end-to-end training is admitted by resorting to the straight-through (ST) discrete gradient estimator. Experimental results on several benchmark datasets demonstrate that the proposed methods, especially the one using Bernoulli mixture priors, consistently outperform existing ones by a substantial margin.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11078](http://arxiv.org/abs/1908.11078)

##### PDF
[http://arxiv.org/pdf/1908.11078](http://arxiv.org/pdf/1908.11078)

