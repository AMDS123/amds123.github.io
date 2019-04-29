---
layout: post
title: "Escaping Plato's Cave using Adversarial Training: 3D Shape From Unstructured 2D Image Collections"
date: 2019-04-26 09:37:44
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Relation
author: Philipp Henzler, Niloy Mitra, Tobias Ritschel
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce PlatonicGAN to discover the 3D structure of an object class from an unstructured collection of 2D images, i.e. neither any relation between the images is available nor additional information about the images is known. The key idea is to train a deep neural network to generate 3D shapes which rendered to images are indistinguishable from ground truth images (for a discriminator) under various camera models (i.e. rendering layers) and camera poses. Discriminating 2D images instead of 3D shapes allows tapping into unstructured 2D photo collections instead of relying on curated (e.g., aligned, annotated, etc.) 3D data sets. To establish constraints between 2D image observation and their 3D interpretation, we suggest a family of rendering layers that are effectively differentiable. This family includes visual hull, absorption-only (akin to x-ray), and emission-absorption. We can successfully reconstruct 3D shapes from unstructured 2D images and extensively evaluate PlatonicGAN on a range of synthetic and real data sets achieving consistent improvements over baseline methods. We can also show that our method with additional 3D supervision further improves result quality and even surpasses the performance of 3D supervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11606](http://arxiv.org/abs/1811.11606)

##### PDF
[http://arxiv.org/pdf/1811.11606](http://arxiv.org/pdf/1811.11606)

