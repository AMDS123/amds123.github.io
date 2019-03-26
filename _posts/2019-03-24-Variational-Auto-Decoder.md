---
layout: post
title: "Variational Auto-Decoder"
date: 2019-03-24 00:39:41
categories: arXiv_AI
tags: arXiv_AI Optimization Inference
author: Amir Zadeh, Yao-Chong Lim, Paul Pu Liang, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a generative model from partial data (data with missingness) is a challenging area of machine learning research. We study a specific implementation of the Auto-Encoding Variational Bayes (AEVB) algorithm, named in this paper as a Variational Auto-Decoder (VAD). VAD is a generic framework which uses Variational Bayes and Markov Chain Monte Carlo (MCMC) methods to learn a generative model from partial data. The main distinction between VAD and Variational Auto-Encoder (VAE) is the encoder component, as VAD does not have one. Using a proposed efficient inference method from a multivariate Gaussian approximate posterior, VAD models allow inference to be performed via simple gradient ascent rather than MCMC sampling from a probabilistic decoder. This technique reduces the inference computational cost, allows for using more complex optimization techniques during latent space inference (which are shown to be crucial due to a high degree of freedom in the VAD latent space), and keeps the framework simple to implement. Through extensive experiments over several datasets and different missing ratios, we show that encoders cannot efficiently marginalize the input volatility caused by imputed missing values. We study multimodal datasets in this paper, which is a particular area of impact for VAD models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00840](http://arxiv.org/abs/1903.00840)

##### PDF
[http://arxiv.org/pdf/1903.00840](http://arxiv.org/pdf/1903.00840)

