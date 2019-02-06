---
layout: post
title: "Approximate Newton-based statistical inference using only stochastic gradients"
date: 2019-02-05 15:23:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference
author: Tianyang Li, Anastasios Kyrillidis, Liu Liu, Constantine Caramanis
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel statistical inference framework for convex empirical risk minimization, using approximate stochastic Newton steps. The proposed algorithm is based on the notion of finite differences and allows the approximation of a Hessian-vector product from first-order information. In theory, our method efficiently computes the statistical error covariance in $M$-estimation, both for unregularized convex learning problems and high-dimensional LASSO regression, without using exact second order information, or resampling the entire data set. We also present a stochastic gradient sampling scheme for statistical inference in non-i.i.d. time series analysis, where we sample contiguous blocks of indices. In practice, we demonstrate the effectiveness of our framework on large-scale machine learning problems, that go even beyond convexity: as a highlight, our work can be used to detect certain adversarial attacks on neural networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08920](http://arxiv.org/abs/1805.08920)

##### PDF
[http://arxiv.org/pdf/1805.08920](http://arxiv.org/pdf/1805.08920)

