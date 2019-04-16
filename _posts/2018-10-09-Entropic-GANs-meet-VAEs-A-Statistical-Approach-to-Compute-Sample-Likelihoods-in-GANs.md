---
layout: post
title: "Entropic GANs meet VAEs: A Statistical Approach to Compute Sample Likelihoods in GANs"
date: 2018-10-09 17:27:20
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Inference Deep_Learning
author: Yogesh Balaji, Hamed Hassani, Rama Chellappa, Soheil Feizi
mathjax: true
---

* content
{:toc}

##### Abstract
Building on the success of deep learning, two modern approaches to learn a probability model of the observed data are Generative Adversarial Networks (GANs) and Variational AutoEncoders (VAEs). VAEs consider an explicit probability model for the data and compute a generative distribution by maximizing a variational lower-bound on the log-likelihood function. GANs, however, compute a generative model by minimizing a distance between observed and generated probability distributions without considering an explicit model for the observed data. The lack of having explicit probability models in GANs prohibits computation of sample likelihoods in their frameworks and limits their use in statistical inference problems. In this work, we show that an optimal transport GAN with the entropy regularization can be viewed as a generative model that maximizes a lower-bound on average sample likelihoods, an approach that VAEs are based on. In particular, our proof constructs an explicit probability model for GANs that can be used to compute likelihood statistics within GAN's framework. Our numerical results on several datasets demonstrate consistent trends with the proposed theory.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04147](https://arxiv.org/abs/1810.04147)

##### PDF
[https://arxiv.org/pdf/1810.04147](https://arxiv.org/pdf/1810.04147)

