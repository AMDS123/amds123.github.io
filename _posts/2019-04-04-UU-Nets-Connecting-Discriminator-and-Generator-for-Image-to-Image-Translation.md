---
layout: post
title: "UU-Nets Connecting Discriminator and Generator for Image to Image Translation"
date: 2019-04-04 17:25:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Wu Jionghao
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial generative model have successfully manifest itself in image synthesis. However, the performance deteriorate and unstable, because discriminator is far stable than generator, and it is hard to control the game between the two modules. Various methods have been introduced to tackle the problem such as WGAN, Relativistic GAN and their successors by adding or restricting the loss function, which certainly help balance the min-max game, but they all focused on the loss function ignoring the intrinsic structure limitation. We present a UU-Net architecture inspired by U-net bridging the encoder and the decoder, UU-Net composed by two U-Net liked modules respectively served as generator and discriminator. Because the modules in U-net are symmetrical, therefore it shares weights easily between all four components. Thanks to UU-net's modules identical and symmetric property, we could not only carried the features from inner generator's encoder to its decoder, but also to the discriminator's encoder and decoder. By this design, it give us more control and condition flexibility to intervene the process between the generator and the discriminator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02675](http://arxiv.org/abs/1904.02675)

##### PDF
[http://arxiv.org/pdf/1904.02675](http://arxiv.org/pdf/1904.02675)

