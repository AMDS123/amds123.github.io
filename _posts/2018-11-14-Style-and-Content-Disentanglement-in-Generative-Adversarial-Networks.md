---
layout: post
title: "Style and Content Disentanglement in Generative Adversarial Networks"
date: 2018-11-14 03:25:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hadi Kazemi, Seyed Mehdi Iranmanesh, Nasser M. Nasrabadi
mathjax: true
---

* content
{:toc}

##### Abstract
Disentangling factors of variation within data has become a very challenging problem for image generation tasks. Current frameworks for training a Generative Adversarial Network (GAN), learn to disentangle the representations of the data in an unsupervised fashion and capture the most significant factors of the data variations. However, these approaches ignore the principle of content and style disentanglement in image generation, which means their learned latent code may alter the content and style of the generated images at the same time. This paper describes the Style and Content Disentangled GAN (SC-GAN), a new unsupervised algorithm for training GANs that learns disentangled style and content representations of the data. We assume that the representation of an image can be decomposed into a content code that represents the geometrical information of the data, and a style code that captures textural properties. Consequently, by fixing the style portion of the latent representation, we can generate diverse images in a particular style. Reversely, we can set the content code and generate a specific scene in a variety of styles. The proposed SC-GAN has two components: a content code which is the input to the generator, and a style code which modifies the scene style through modification of the Adaptive Instance Normalization (AdaIN) layers' parameters. We evaluate the proposed SC-GAN framework on a set of baseline datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05621](http://arxiv.org/abs/1811.05621)

##### PDF
[http://arxiv.org/pdf/1811.05621](http://arxiv.org/pdf/1811.05621)

