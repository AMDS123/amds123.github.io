---
layout: post
title: "TraVeLGAN: Image-to-image Translation by Transformation Vector Learning"
date: 2019-02-25 21:48:32
categories: arXiv_CV
tags: arXiv_CV GAN Image_Generation
author: Matthew Amodio, Smita Krishnaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
Interest in image-to-image translation has grown substantially in recent years with the success of unsupervised models based on the cycle-consistency assumption. The achievements of these models have been limited to a particular subset of domains where this assumption yields good results, namely homogeneous domains that are characterized by style or texture differences. We tackle the challenging problem of image-to-image translation where the domains are defined by high-level shapes and contexts, as well as including significant clutter and heterogeneity. For this purpose, we introduce a novel GAN based on preserving intra-domain vector transformations in a latent space learned by a siamese network. The traditional GAN system introduced a discriminator network to guide the generator into generating images in the target domain. To this two-network system we add a third: a siamese network that guides the generator so that each original image shares semantics with its generated version. With this new three-network system, we no longer need to constrain the generators with the ubiquitous cycle-consistency restraint. As a result, the generators can learn mappings between more complex domains that differ from each other by large differences - not just style or texture.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09631](http://arxiv.org/abs/1902.09631)

##### PDF
[http://arxiv.org/pdf/1902.09631](http://arxiv.org/pdf/1902.09631)

