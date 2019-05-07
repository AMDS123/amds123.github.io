---
layout: post
title: "Do GANs actually learn the distribution? An empirical study"
date: 2017-07-01 03:25:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Sanjeev Arora, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Do GANS (Generative Adversarial Nets) actually learn the target distribution? The foundational paper of (Goodfellow et al 2014) suggested they do, if they were given sufficiently large deep nets, sample size, and computation time. A recent theoretical analysis in Arora et al (to appear at ICML 2017) raised doubts whether the same holds when discriminator has finite size. It showed that the training objective can approach its optimum value even if the generated distribution has very low support ---in other words, the training objective is unable to prevent mode collapse. The current note reports experiments suggesting that such problems are not merely theoretical. It presents empirical evidence that well-known GANs approaches do learn distributions of fairly low support, and thus presumably are not learning the target distribution. The main technical contribution is a new proposed test, based upon the famous birthday paradox, for estimating the support size of the generated distribution.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.08224](https://arxiv.org/abs/1706.08224)

##### PDF
[https://arxiv.org/pdf/1706.08224](https://arxiv.org/pdf/1706.08224)

