---
layout: post
title: "Automated Multiscale 3D Feature Learning for Vessels Segmentation in Thorax CT Images"
date: 2019-01-06 16:06:32
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tomasz Konopczy&#x144;ski, Thorben Kr&#xf6;ger, Lei Zheng, Christoph S. Garbe, J&#xfc;rgen Hesser
mathjax: true
---

* content
{:toc}

##### Abstract
We address the vessel segmentation problem by building upon the multiscale feature learning method of Kiros et al., which achieves the current top score in the VESSEL12 MICCAI challenge. Following their idea of feature learning instead of hand-crafted filters, we have extended the method to learn 3D features. The features are learned in an unsupervised manner in a multi-scale scheme using dictionary learning via least angle regression. The 3D feature kernels are further convolved with the input volumes in order to create feature maps. Those maps are used to train a supervised classifier with the annotated voxels. In order to process the 3D data with a large number of filters a parallel implementation has been developed. The algorithm has been applied on the example scans and annotations provided by the VESSEL12 challenge. We have compared our setup with Kiros et al. by running their implementation. Our current results show an improvement in accuracy over the slice wise method from 96.66$\pm$1.10% to 97.24$\pm$0.90%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01562](http://arxiv.org/abs/1901.01562)

##### PDF
[http://arxiv.org/pdf/1901.01562](http://arxiv.org/pdf/1901.01562)

