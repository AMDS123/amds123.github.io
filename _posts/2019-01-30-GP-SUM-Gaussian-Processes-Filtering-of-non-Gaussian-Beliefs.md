---
layout: post
title: "GP-SUM. Gaussian Processes Filtering of non-Gaussian Beliefs"
date: 2019-01-30 23:28:07
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Maria Bauza, Alberto Rodriguez
mathjax: true
---

* content
{:toc}

##### Abstract
This work studies the problem of stochastic dynamic filtering and state propagation with complex beliefs. The main contribution is GP-SUM, a filtering algorithm tailored to dynamic systems and observation models expressed as Gaussian Processes (GP), and to states represented as a weighted sum of Gaussians. The key attribute of GP-SUM is that it does not rely on linearizations of the dynamic or observation models, or on unimodal Gaussian approximations of the belief, hence enables tracking complex state distributions. The algorithm can be seen as a combination of a sampling-based filter with a probabilistic Bayes filter. On the one hand, GP-SUM operates by sampling the state distribution and propagating each sample through the dynamic system and observation models. On the other hand, it achieves effective sampling and accurate probabilistic propagation by relying on the GP form of the system, and the sum-of-Gaussian form of the belief. We show that GP-SUM outperforms several GP-Bayes and Particle Filters on a standard benchmark. We also demonstrate its use in a pushing task, predicting with experimental accuracy the naturally occurring non-Gaussian distributions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.08120](http://arxiv.org/abs/1709.08120)

##### PDF
[http://arxiv.org/pdf/1709.08120](http://arxiv.org/pdf/1709.08120)

