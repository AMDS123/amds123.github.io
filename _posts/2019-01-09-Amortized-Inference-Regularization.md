---
layout: post
title: "Amortized Inference Regularization"
date: 2019-01-09 18:56:45
categories: arXiv_AI
tags: arXiv_AI Regularization Represenation_Learning Inference
author: Rui Shu, Hung H. Bui, Shengjia Zhao, Mykel J. Kochenderfer, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
The variational autoencoder (VAE) is a popular model for density estimation and representation learning. Canonically, the variational principle suggests to prefer an expressive inference model so that the variational approximation is accurate. However, it is often overlooked that an overly-expressive inference model can be detrimental to the test set performance of both the amortized posterior approximator and, more importantly, the generative density estimator. In this paper, we leverage the fact that VAEs rely on amortized inference and propose techniques for amortized inference regularization (AIR) that control the smoothness of the inference model. We demonstrate that, by applying AIR, it is possible to improve VAE generalization on both inference and generative performance. Our paper challenges the belief that amortized inference is simply a mechanism for approximating maximum likelihood training and illustrates that regularization of the amortization family provides a new direction for understanding and improving generalization in VAEs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08913](http://arxiv.org/abs/1805.08913)

##### PDF
[http://arxiv.org/pdf/1805.08913](http://arxiv.org/pdf/1805.08913)

