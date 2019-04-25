---
layout: post
title: "InGAN: Capturing and Remapping the 'DNA' of a Natural Image"
date: 2019-04-24 11:38:55
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Assaf Shocher, Shai Bagon, Phillip Isola, Michal Irani
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) typically learn a distribution of images in a large image dataset, and are then able to generate new images from this distribution. However, each natural image has its own internal statistics, captured by its unique distribution of patches. In this paper we propose an "Internal GAN" (InGAN) - an image-specific GAN - which trains on a single input image and learns its internal distribution of patches. It is then able to synthesize a plethora of new natural images of significantly different sizes, shapes and aspect-ratios - all with the same internal patch-distribution (same "DNA") as the input image. In particular, despite large changes in global size/shape of the image, all elements inside the image maintain their local size/shape. InGAN is fully unsupervised, requiring no additional data other than the input image itself. Once trained on the input image, it can remap the input to any size or shape in a single feedforward pass, while preserving the same internal patch distribution. InGAN provides a unified framework for a variety of tasks, bridging the gap between textures and natural images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00231](http://arxiv.org/abs/1812.00231)

##### PDF
[http://arxiv.org/pdf/1812.00231](http://arxiv.org/pdf/1812.00231)

