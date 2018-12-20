---
layout: post
title: "An Empirical Study of Generative Models with Encoders"
date: 2018-12-19 12:28:47
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Paul K. Rubenstein, Yunpeng Li, Dominik Roblek
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are capable of producing high quality image samples. However, unlike variational autoencoders (VAEs), GANs lack encoders that provide the inverse mapping for the generators, i.e., encode images back to the latent space. In this work, we consider adversarially learned generative models that also have encoders. We evaluate models based on their ability to produce high quality samples and reconstructions of real images. Our main contributions are twofold: First, we find that the baseline Bidirectional GAN (BiGAN) can be improved upon with the addition of an autoencoder loss, at the expense of an extra hyper-parameter to tune. Second, we show that comparable performance to BiGAN can be obtained by simply training an encoder to invert the generator of a normal GAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07909](http://arxiv.org/abs/1812.07909)

##### PDF
[http://arxiv.org/pdf/1812.07909](http://arxiv.org/pdf/1812.07909)

