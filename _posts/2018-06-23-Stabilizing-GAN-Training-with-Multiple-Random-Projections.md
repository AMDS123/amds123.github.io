---
layout: post
title: "Stabilizing GAN Training with Multiple Random Projections"
date: 2018-06-23 00:53:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Behnam Neyshabur, Srinadh Bhojanapalli, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Training generative adversarial networks is unstable in high-dimensions as the true data distribution tends to be concentrated in a small fraction of the ambient space. The discriminator is then quickly able to classify nearly all generated samples as fake, leaving the generator without meaningful gradients and causing it to deteriorate after a point in training. In this work, we propose training a single generator simultaneously against an array of discriminators, each of which looks at a different random low-dimensional projection of the data. Individual discriminators, now provided with restricted views of the input, are unable to reject generated samples perfectly and continue to provide meaningful gradients to the generator throughout training. Meanwhile, the generator learns to produce samples consistent with the full data distribution to satisfy all discriminators simultaneously. We demonstrate the practical utility of this approach experimentally, and show that it is able to produce image samples with higher quality than traditional training with a single discriminator.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.07831](https://arxiv.org/abs/1705.07831)

##### PDF
[https://arxiv.org/pdf/1705.07831](https://arxiv.org/pdf/1705.07831)

