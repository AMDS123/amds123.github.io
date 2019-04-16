---
layout: post
title: "Mixed batches and symmetric discriminators for GAN training"
date: 2018-06-19 12:39:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Thomas Lucas, Corentin Tallec, Jakob Verbeek, Yann Ollivier
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are pow- erful generative models based on providing feed- back to a generative network via a discriminator network. However, the discriminator usually as- sesses individual samples. This prevents the dis- criminator from accessing global distributional statistics of generated samples, and often leads to mode dropping: the generator models only part of the target distribution. We propose to feed the discriminator with mixed batches of true and fake samples, and train it to predict the ratio of true samples in the batch. The latter score does not depend on the order of samples in a batch. Rather than learning this invariance, we introduce a generic permutation-invariant discriminator ar- chitecture. This architecture is provably a uni- versal approximator of all symmetric functions. Experimentally, our approach reduces mode col- lapse in GANs on two synthetic datasets, and obtains good results on the CIFAR10 and CelebA datasets, both qualitatively and quantitatively.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.07185](https://arxiv.org/abs/1806.07185)

##### PDF
[https://arxiv.org/pdf/1806.07185](https://arxiv.org/pdf/1806.07185)

