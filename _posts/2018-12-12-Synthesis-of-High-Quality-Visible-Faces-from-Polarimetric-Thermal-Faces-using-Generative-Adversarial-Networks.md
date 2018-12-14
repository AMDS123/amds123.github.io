---
layout: post
title: "Synthesis of High-Quality Visible Faces from Polarimetric Thermal Faces using Generative Adversarial Networks"
date: 2018-12-12 21:04:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: He Zhang, Benjamin S. Riggan, Shuowen Hu, Nathaniel J. Short, Vishal M.Patel
mathjax: true
---

* content
{:toc}

##### Abstract
The large domain discrepancy between faces captured in polarimetric (or conventional) thermal and visible domain makes cross-domain face verification a highly challenging problem for human examiners as well as computer vision algorithms. Previous approaches utilize either a two-step procedure (visible feature estimation and visible image reconstruction) or an input-level fusion technique, where different Stokes images are concatenated and used as a multi-channel input to synthesize the visible image given the corresponding polarimetric signatures. Although these methods have yielded improvements, we argue that input-level fusion alone may not be sufficient to realize the full potential of the available Stokes images. We propose a Generative Adversarial Networks (GAN) based multi-stream feature-level fusion technique to synthesize high-quality visible images from prolarimetric thermal images. The proposed network consists of a generator sub-network, constructed using an encoder-decoder network based on dense residual blocks, and a multi-scale discriminator sub-network. The generator network is trained by optimizing an adversarial loss in addition to a perceptual loss and an identity preserving loss to enable photo realistic generation of visible images while preserving discriminative characteristics. An extended dataset consisting of polarimetric thermal facial signatures of 111 subjects is also introduced. Multiple experiments evaluated on different experimental protocols demonstrate that the proposed method achieves state-of-the-art performance. Code will be made available at https://github.com/hezhangsprinter.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05155](http://arxiv.org/abs/1812.05155)

##### PDF
[http://arxiv.org/pdf/1812.05155](http://arxiv.org/pdf/1812.05155)

