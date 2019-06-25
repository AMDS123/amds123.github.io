---
layout: post
title: "SeGMA: Semi-Supervised Gaussian Mixture Auto-Encoder"
date: 2019-06-21 21:23:12
categories: arXiv_AI
tags: arXiv_AI Style_Transfer
author: Marek &#x15a;mieja, Maciej Wo&#x142;czyk, Jacek Tabor, Bernhard C. Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a semi-supervised generative model, SeGMA, which learns a joint probability distribution of data and their classes and which is implemented in a typical Wasserstein auto-encoder framework. We choose a mixture of Gaussians as a target distribution in latent space, which provides a natural splitting of data into clusters. To connect Gaussian components with correct classes, we use a small amount of labeled data and a Gaussian classifier induced by the target distribution. SeGMA is optimized efficiently due to the use of Cramer-Wold distance as a maximum mean discrepancy penalty, which yields a closed-form expression for a mixture of spherical Gaussian components and thus obviates the need of sampling. While SeGMA preserves all properties of its semi-supervised predecessors and achieves at least as good generative performance on standard benchmark data sets, it presents additional features: (a) interpolation between any pair of points in the latent space produces realistically-looking samples; (b) combining the interpolation property with disentangled class and style variables, SeGMA is able to perform a continuous style transfer from one class to another; (c) it is possible to change the intensity of class characteristics in a data point by moving the latent representation of the data point away from specific Gaussian components.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09333](http://arxiv.org/abs/1906.09333)

##### PDF
[http://arxiv.org/pdf/1906.09333](http://arxiv.org/pdf/1906.09333)

