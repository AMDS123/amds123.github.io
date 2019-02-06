---
layout: post
title: "A variance modeling framework based on variational autoencoders for speech enhancement"
date: 2019-02-05 09:36:18
categories: arXiv_SD
tags: arXiv_SD Deep_Learning
author: Simon Leglaive, Laurent Girin, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the problem of enhancing speech signals in noisy mixtures using a source separation approach. We explore the use of neural networks as an alternative to a popular speech variance model based on supervised non-negative matrix factorization (NMF). More precisely, we use a variational autoencoder as a speaker-independent supervised generative speech model, highlighting the conceptual similarities that this approach shares with its NMF-based counterpart. In order to be free of generalization issues regarding the noisy recording environments, we follow the approach of having a supervised model only for the target speech signal, the noise model being based on unsupervised NMF. We develop a Monte Carlo expectation-maximization algorithm for inferring the latent variables in the variational autoencoder and estimating the unsupervised model parameters. Experiments show that the proposed method outperforms a semi-supervised NMF baseline and a state-of-the-art fully supervised deep learning approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01605](http://arxiv.org/abs/1902.01605)

##### PDF
[http://arxiv.org/pdf/1902.01605](http://arxiv.org/pdf/1902.01605)

