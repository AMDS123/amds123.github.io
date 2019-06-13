---
layout: post
title: "Inferring 3D Shapes from Image Collections using Adversarial Networks"
date: 2019-06-11 00:28:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN
author: Matheus Gadelha, Aartika Rai, Subhransu Maji, Rui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of learning a probabilistic distribution over three-dimensional shapes given two-dimensional views of multiple objects taken from unknown viewpoints. Our approach called projective generative adversarial network (PrGAN) trains a deep generative model of 3D shapes whose projections (or renderings) match the distributions of the provided 2D distribution. The addition of a differentiable projection module allows us to infer the underlying 3D shape distribution without access to any explicit 3D or viewpoint annotation during the learning phase. We show that our approach produces 3D shapes of comparable quality to GANs trained directly on 3D data. %for a number of shape categoriesincluding chairs, airplanes, and cars. Experiments also show that the disentangled representation of 2D shapes into geometry and viewpoint leads to a good generative model of 2D shapes. The key advantage of our model is that it estimates 3D shape, viewpoint, and generates novel views from an input image in a completely unsupervised manner. We further investigate how the generative models can be improved if additional information such as depth, viewpoint or part segmentations is available at training time. To this end, we present new differentiable projection operators that can be used by PrGAN to learn better 3D generative models. Our experiments show that our method can successfully leverage extra visual cues to create more diverse and accurate shapes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04910](http://arxiv.org/abs/1906.04910)

##### PDF
[http://arxiv.org/pdf/1906.04910](http://arxiv.org/pdf/1906.04910)

