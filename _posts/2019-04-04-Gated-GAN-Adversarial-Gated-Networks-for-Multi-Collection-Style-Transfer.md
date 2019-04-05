---
layout: post
title: "Gated-GAN: Adversarial Gated Networks for Multi-Collection Style Transfer"
date: 2019-04-04 01:20:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer
author: Xinyuan Chen, Chang Xu, Xiaokang Yang, Li Song, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Style transfer describes the rendering of an image semantic content as different artistic styles. Recently, generative adversarial networks (GANs) have emerged as an effective approach in style transfer by adversarially training the generator to synthesize convincing counterfeits. However, traditional GAN suffers from the mode collapse issue, resulting in unstable training and making style transfer quality difficult to guarantee. In addition, the GAN generator is only compatible with one style, so a series of GANs must be trained to provide users with choices to transfer more than one kind of style. In this paper, we focus on tackling these challenges and limitations to improve style transfer. We propose adversarial gated networks (Gated GAN) to transfer multiple styles in a single model. The generative networks have three modules: an encoder, a gated transformer, and a decoder. Different styles can be achieved by passing input images through different branches of the gated transformer. To stabilize training, the encoder and decoder are combined as an autoencoder to reconstruct the input images. The discriminative networks are used to distinguish whether the input image is a stylized or genuine image. An auxiliary classifier is used to recognize the style categories of transferred images, thereby helping the generative networks generate images in multiple styles. In addition, Gated GAN makes it possible to explore a new style by investigating styles learned from artists or genres. Our extensive experiments demonstrate the stability and effectiveness of the proposed model for multistyle transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02296](http://arxiv.org/abs/1904.02296)

##### PDF
[http://arxiv.org/pdf/1904.02296](http://arxiv.org/pdf/1904.02296)

