---
layout: post
title: "Robustness Against Outliers For Deep Neural Networks By Gradient Conjugate Priors"
date: 2019-05-21 07:10:16
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Pavel Gurevich, Hannes Stuke
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze a new robust method for the reconstruction of probability distributions of observed data in the presence of output outliers. It is based on a so-called gradient conjugate prior (GCP) network which outputs the parameters of a prior. By rigorously studying the dynamics of the GCP learning process, we derive an explicit formula for correcting the obtained variance of the marginal distribution and removing the bias caused by outliers in the training set. Assuming a Gaussian (input-dependent) ground truth distribution contaminated with a proportion $\varepsilon$ of outliers, we show that the fitted mean is in a $c e^{-1/\varepsilon}$-neighborhood of the ground truth mean and the corrected variance is in a $b\varepsilon$-neighborhood of the ground truth variance, whereas the uncorrected variance of the marginal distribution can even be infinite. We explicitly find $b$ as a function of the output of the GCP network, without a priori knowledge of the outliers (possibly input-dependent) distribution. Experiments with synthetic and real-world data sets indicate that the GCP network fitted with a standard optimizer outperforms other robust methods for regression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08464](http://arxiv.org/abs/1905.08464)

##### PDF
[http://arxiv.org/pdf/1905.08464](http://arxiv.org/pdf/1905.08464)

