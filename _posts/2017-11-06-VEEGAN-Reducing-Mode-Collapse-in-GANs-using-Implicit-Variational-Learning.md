---
layout: post
title: "VEEGAN: Reducing Mode Collapse in GANs using Implicit Variational Learning"
date: 2017-11-06 21:24:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Akash Srivastava, Lazar Valkov, Chris Russell, Michael U. Gutmann, Charles Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models provide powerful tools for distributions over complicated manifolds, such as those of natural images. But many of these methods, including generative adversarial networks (GANs), can be difficult to train, in part because they are prone to mode collapse, which means that they characterize only a few modes of the true distribution. To address this, we introduce VEEGAN, which features a reconstructor network, reversing the action of the generator by mapping from data to noise. Our training objective retains the original asymptotic consistency guarantee of GANs, and can be interpreted as a novel autoencoder loss over the noise. In sharp contrast to a traditional autoencoder over data points, VEEGAN does not require specifying a loss function over the data, but rather only over the representations, which are standard normal by assumption. On an extensive set of synthetic and real world image datasets, VEEGAN indeed resists mode collapsing to a far greater extent than other recent GAN variants, and produces more realistic samples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.07761](https://arxiv.org/abs/1705.07761)

##### PDF
[https://arxiv.org/pdf/1705.07761](https://arxiv.org/pdf/1705.07761)

