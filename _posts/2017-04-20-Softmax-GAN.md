---
layout: post
title: "Softmax GAN"
date: 2017-04-20 15:35:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Min Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Softmax GAN is a novel variant of Generative Adversarial Network (GAN). The key idea of Softmax GAN is to replace the classification loss in the original GAN with a softmax cross-entropy loss in the sample space of one single batch. In the adversarial learning of $N$ real training samples and $M$ generated samples, the target of discriminator training is to distribute all the probability mass to the real samples, each with probability $\frac{1}{M}$, and distribute zero probability to generated data. In the generator training phase, the target is to assign equal probability to all data points in the batch, each with probability $\frac{1}{M+N}$. While the original GAN is closely related to Noise Contrastive Estimation (NCE), we show that Softmax GAN is the Importance Sampling version of GAN. We futher demonstrate with experiments that this simple change stabilizes GAN training.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.06191](https://arxiv.org/abs/1704.06191)

##### PDF
[https://arxiv.org/pdf/1704.06191](https://arxiv.org/pdf/1704.06191)

