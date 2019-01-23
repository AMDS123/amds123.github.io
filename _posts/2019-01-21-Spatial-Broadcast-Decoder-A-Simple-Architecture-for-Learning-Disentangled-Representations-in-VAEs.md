---
layout: post
title: "Spatial Broadcast Decoder: A Simple Architecture for Learning Disentangled Representations in VAEs"
date: 2019-01-21 18:08:49
categories: arXiv_CV
tags: arXiv_CV CNN
author: Nicholas Watters, Loic Matthey, Christopher P. Burgess, Alexander Lerchner
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple neural rendering architecture that helps variational autoencoders (VAEs) learn disentangled representations. Instead of the deconvolutional network typically used in the decoder of VAEs, we tile (broadcast) the latent vector across space, concatenate fixed X- and Y-"coordinate" channels, and apply a fully convolutional network with 1x1 stride. This provides an architectural prior for dissociating positional from non-positional features in the latent distribution of VAEs, yet without providing any explicit supervision to this effect. We show that this architecture, which we term the Spatial Broadcast decoder, improves disentangling, reconstruction accuracy, and generalization to held-out regions in data space. It provides a particularly dramatic benefit when applied to datasets with small objects. We also emphasize a method for visualizing learned latent spaces that helped us diagnose our models and may prove useful for others aiming to assess data representations. Finally, we show the Spatial Broadcast Decoder is complementary to state-of-the-art (SOTA) disentangling techniques and when incorporated improves their performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07017](http://arxiv.org/abs/1901.07017)

##### PDF
[http://arxiv.org/pdf/1901.07017](http://arxiv.org/pdf/1901.07017)

