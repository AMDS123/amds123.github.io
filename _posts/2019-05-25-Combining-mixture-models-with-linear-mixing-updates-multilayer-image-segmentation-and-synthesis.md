---
layout: post
title: "Combining mixture models with linear mixing updates: multilayer image segmentation and synthesis"
date: 2019-05-25 16:55:19
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Jonathan Vacher, Ruben Coen-Cagli
mathjax: true
---

* content
{:toc}

##### Abstract
Finite mixture models for clustering can often be improved by adding a regularization that is specific to the topology of the data. For instance, mixtures are common in unsupervised image segmentation, and typically rely on averaging the posterior mixing probabilities of spatially adjacent data points (i.e. smoothing). However, this approach has had limited success with natural images. Here we make three contributions. First, we show that a Dirichlet prior with an appropriate choice of parameters allows -- using the Expectation-Maximization approach -- to define any linear update rule for the mixing probabilities, including many smoothing regularizations as special cases. Second, we demonstrate how to use this flexible design of the update rule to propagate segmentation information across layers of a deep network, and to train mixtures jointly across layers. Third, we compare the standard Gaussian mixture and the Student-t mixture, which is known to better capture the statistics of low-level visual features. We show that our models achieve competitive performance in natural image segmentation, with the Student-t mixtures reaching state-of-the art on boundaries scores. We also demonstrate how to exploit the resulting multilayer probabilistic generative model to synthesize naturalistic images beyond uniform textures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10629](http://arxiv.org/abs/1905.10629)

##### PDF
[http://arxiv.org/pdf/1905.10629](http://arxiv.org/pdf/1905.10629)

