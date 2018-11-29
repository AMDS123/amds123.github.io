---
layout: post
title: "Escaping Plato's Cave using Adversarial Training: 3D Shape From Unstructured 2D Image Collections"
date: 2018-11-28 14:58:22
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Philipp Henzler, Niloy Mitra, Tobias Ritschel
mathjax: true
---

* content
{:toc}

##### Abstract
We develop PlatonicGAN to discover 3D structure of an object class from an unstructured collection of 2D images. The key idea is to learn a deep neural network that generates 3D shapes that are never objectionable to a discriminator looking only at its 2D projections, i.e. renderings of the generated volumes. Using such a 2D instead of a 3D discriminator allows tapping into massive 2D image collections instead of relying on much smaller 3D data sets. To establish constraints between 2D image observation and their 3D interpretation we suggest a family of rendering layers that are effectively back-propagatable. This family includes visual hull, absorption-only (akin to x-ray), and emission-absorption (that can resolve occlusion if multiple 3D points project to the same 2D pixel). These layers are studied both on synthetic and real data in an application to reconstruct of 3D shape from 2D images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11606](http://arxiv.org/abs/1811.11606)

##### PDF
[http://arxiv.org/pdf/1811.11606](http://arxiv.org/pdf/1811.11606)

