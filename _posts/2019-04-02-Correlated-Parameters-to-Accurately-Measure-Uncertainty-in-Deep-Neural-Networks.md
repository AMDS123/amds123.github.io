---
layout: post
title: "Correlated Parameters to Accurately Measure Uncertainty in Deep Neural Networks"
date: 2019-04-02 11:06:50
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Konstantin Posch, J&#xfc;rgen Pilz
mathjax: true
---

* content
{:toc}

##### Abstract
In this article a novel approach for training deep neural networks using Bayesian techniques is presented. The Bayesian methodology allows for an easy evaluation of model uncertainty and additionally is robust to overfitting. These are commonly the two main problems classical, i.e. non-Bayesian, architectures have to struggle with. The proposed approach applies variational inference in order to approximate the intractable posterior distribution. In particular, the variational distribution is defined as product of multiple multivariate normal distributions with tridiagonal covariance matrices. Each single normal distribution belongs either to the weights, or to the biases corresponding to one network layer. The layer-wise a posteriori variances are defined based on the corresponding expectation values and further the correlations are assumed to be identical. Therefore, only a few additional parameters need to be optimized compared to non-Bayesian settings. The novel approach is successfully evaluated on basis of the popular benchmark datasets MNIST and CIFAR-10.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01334](http://arxiv.org/abs/1904.01334)

##### PDF
[http://arxiv.org/pdf/1904.01334](http://arxiv.org/pdf/1904.01334)

