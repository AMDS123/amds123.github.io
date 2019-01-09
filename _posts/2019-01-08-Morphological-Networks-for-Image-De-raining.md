---
layout: post
title: "Morphological Networks for Image De-raining"
date: 2019-01-08 17:13:47
categories: arXiv_CV
tags: arXiv_CV
author: Ranjan Mondal, Pulak Purkait, Sanchayan Santra, Bhabatosh Chanda
mathjax: true
---

* content
{:toc}

##### Abstract
Mathematical morphological methods have successfully been applied to filter out (emphasize or remove) different structures of an image. However, it is argued that these methods could be suitable for the task only if the type and order of the filter(s) as well as the shape and size of operator kernel are designed properly. Thus the existing filtering operators are problem (instance) specific and are designed by the domain experts. In this work we propose a morphological network that emulates classical morphological filtering consisting of a series of erosion and dilation operators with trainable structuring elements. We evaluate the proposed network for image de-raining task where the SSIM and mean absolute error (MAE) loss corresponding to predicted and ground-truth clean image is back-propagated through the network to train the structuring elements. We observe that a single morphological network can de-rain an image with any arbitrary shaped rain-droplets and achieves similar performance with the contemporary CNNs for this task with a fraction of trainable parameters (network size). The proposed morphological network(MorphoN) is not designed specifically for de-raining and can readily be applied to similar filtering / noise cleaning tasks. The source code can be found here https://github.com/ranjanZ/2D-Morphological-Network

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02411](http://arxiv.org/abs/1901.02411)

##### PDF
[http://arxiv.org/pdf/1901.02411](http://arxiv.org/pdf/1901.02411)

