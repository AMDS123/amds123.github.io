---
layout: post
title: "Bayesian Subspace Hidden Markov Model for Acoustic Unit Discovery"
date: 2019-04-08 07:48:36
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding
author: Lucas Ondel, Hari Krishna Vydana, Luk&#xe1;&#x161; Burget, Jan &#x10c;ernock&#xfd;
mathjax: true
---

* content
{:toc}

##### Abstract
This work tackles the problem of learning a set of language specific acoustic units from unlabeled speech recordings given a set of labeled recordings from other languages. Our approach may be described by the following two steps procedure: first the model learns the notion of acoustic units from the labelled data and then the model uses its knowledge to find new acoustic units on the target language. We implement this process with the Bayesian Subspace Hidden Markov Model (SHMM), a model akin to the Subspace Gaussian Mixture Model (SGMM) where each low dimensional embedding represents an acoustic unit rather than just a HMM's state. The subspace is trained on 3 languages from the GlobalPhone corpus (German, Polish and Spanish) and the AUs are discovered on the TIMIT corpus. Results, measured in equivalent Phone Error Rate, show that this approach significantly outperforms previous HMM based acoustic units discovery systems and compares favorably with the Variational Auto Encoder-HMM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03876](http://arxiv.org/abs/1904.03876)

##### PDF
[http://arxiv.org/pdf/1904.03876](http://arxiv.org/pdf/1904.03876)

